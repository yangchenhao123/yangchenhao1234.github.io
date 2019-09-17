
  <style>
  * {
    padding: 0;
    margin: 0;
    list-style-type: none;
    text-decoration: none;
}

body {
    background-color: #f6f6f6;
}

.box {
    width: 100%;
    height: 1500px;
}

.top {
    width: 100%;
    height: 50px;
    background-color: red;
    /* position: absolute;
    left: 0;
    top: 0; */
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.left {
    width: 50px;
    height: 50px;
}

.left .meny {
    display: inline-block;
    width: 20px;
    height: 20px;
    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAgCAYAAABgrToAAAAAAXNSR0IArs4c6QAAAHlJREFUWAnt2LEJwDAMRFE5c2ShLOKhsp69h3ISeAI1CnyBiJvA8dwcHu7+mNmrvbWdZivMHAq4dOgW7kDt65y6fiPg1AZnt8kr7haKPAgggAACfxOIskCbKdwabaaAlw0rmhaDAAIIIIBAQYA2U8CLX2kzFcB8m/kAgGUmQShl8pcAAAAASUVORK5CYII)no-repeat;
    background-size: 100% 100%;
    position: absolute;
    /* left: -85%;
    top: -50%; */
    margin: 15px 0 0 10px;
}

.menu-icon {
    width: 50px;
    height: 44px;
    position: absolute;
}

.ssl {
    width: 400px;
    height: 30px;
    position: relative;
    left: 15px;
    border-radius: 25px;
    background-color: white;
}

.ssl input {
    width: 171px;
    height: 28px;
    border: 1px solid transparent;
    outline: none;
    position: relative;
    left: 54px;
}

.jdlogo {
    width: 50px;
    height: 50px;
    position: relative;
    left: -288px;
}

.jdlogo span {
    display: block;
    width: 20px;
    height: 15px;
    background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAeCAYAAABe3VzdAAAAAXNSR0IArs4c6QAAA/tJREFUWAnNmF9oU1ccx8/v5iZXov2nTVOloowJDjfYk4w1SW2xVdDik08iYw8Dqw9j4tsYFMZe3HAMBg593B5mVQSLD0abalL/FcUHNwTFvsjU/HFNW21N0tzfvifNiTf3pqajtc2B8Pv9vvec3/3c8+fec0KiSkm0hyIsuNNazaD6tY0jl8alFm8P/SEEH7Belz5BhJkSRBNw0gjjJOgesxh1Gfqd5kjkH3ubSrFeSVwKDVBgFPWCuR52I36f4EF3ytz5TE4kAsFrgumkb9vWC3TqVE7qlYpWSVwODT25A8BnEn8/fJwKhbrmu+eKAVqANpl5vhpvD57g/ftdFr3gvpchdmmugxjiWZPZTWw2YKybTKKtxGI7eu1DO0RxOnyTev5iFa4dtl5/L4DrWn0DdPZs1noj5SdCoS2c5z4i+oqZ1yhdWpNFHxbdmP9G9CelL/sQt0Sjj/03YkfZo3+KZXRHgby1/MN4V9cmFS87oLqxPxJ50rK+tROvnrtKK1pPLjv7ndJWDFACYBrMkNfYh+F+pYCK9otkd/cG6a8ooATwXbnyjEj8Jn1VMDd1nsnukvGKA0oIN3tOSmstLMxuGdcEYOPI1TEM81MrIDGFagZwDozLVzSJVu7v12qiB+cAKWHtQcxD11Qs1lRDgKKwO7JCZvN5Xy0BOr5qJj6XtQPItM7ae9J3C5GqHUAy26yAWNWzjcPDEwsBdGyBrImWwi9ss1h8bs2FHc5TQHJVQCbhsTaUfoM3V3GnYq+30DjxIvUZgOTOu1SwRRuWQVVA1PGXWkmH6A2Fw6/LtMUGPHvMngKAQ1J7JyD39nqJeXNZY+Z4WbzIIBns7MBGdp8tzbRhuC9L7Z2AyX8n9qLr5eGnVPBhv1UKFumkAzs/MDl/zn4PjcSv9UNDL2X6eQFlYxwVf3YyaGGn9v+VZKCjNyMyt3Hqa7a2Rm9MGobnuNIcL8epnp6Wmek3X2Y58y2erE5VnLMU93mNgXJt4VE6sKcpJ17txk7liMlmu70lVm2eNHFQ9Z68rieDoR9NU6zHim7DUbsNcJvld9DeWMaaxv0LWSDJ5/Hj8UAwj7nlxqJqwBGzEVPjowxPbqmUV2mof8QXjV5UsbS6aXJhBSHJXCk5xVgZEqd9sVjZxlJdsls84NdSK6Qs5psvbaEtUUoQH/LFouftueadg6oi5kQOXfc9zg99SlsqK78W6Nk/Vxvuj/2xmANO3scxB9XNASb/VxnQNfHL2uj1B0pfEktiDC+H3zWPfrrafzQ6IG5jMPDipUlAjeOp/sJ/Jvebm+pGaXBwuhqQptEjDN9NZ73CoE5BTzNTGi+ruCa0u6u8ntG6cLhs7+ds+1b5D7N0Tl8rtx1wAAAAAElFTkSuQmCC)no-repeat;
    background-size: 20px 15px;
    margin: 17px 8px 0 68px;
}

.shuxian {
    height: 16px;
    border: 1px solid gray;
    border-top-color: transparent;
    border-left-color: transparent;
    border-bottom-color: transparent;
    position: relative;
    left: -245px;
}

.fdj {
    width: 28px;
    height: 15px;
    background: url(https://st.360buyimg.com/so/images/search/jd-sprites.png?__inline)no-repeat;
    background-position: -80px 0;
    background-size: 200px;
    position: relative;
    left: -244px;
}

.dl {
    width: 60px;
    height: 44px;
    position: relative;
    left: -10px;
    font-size: 18px;
    color: white;
    position: relative;
    left: -26px;
    top: 13px;
}

/* 轮播图。。。。。。。。。。。。。。。。。。。。。。 */
.lbt {
    width: 350px;
    height: 140px;
    border-radius: 10px;
    margin: 10px auto;
    overflow: hidden;
}

.mais {
    width: 350px;
    height: 140px;
    border-left-color: transparent;
    border-right-color: transparent;
    /* margin: 100px auto; */
    overflow: hidden;
    position: absolute;
    /* top: 185px; */
}

.list {
    width: 1795px;
    position: relative;
    animation: ych 10s linear 0s infinite normal;
    /*         名字 时间 速度 延时 无限播放  方向 */
}

.list:hover {
    animation-play-state: paused;
    /* 暂停动画 */
}

.clearfix:after {
    clear: both;
    height: 0;
    contain: "";
    display: block;
    visibility: hidden;
}

.list>li {
    width: 350px;
    height: 140px;
    float: left;
}

.list img {
    width: 100%;
    height: 100%;
    border-radius: 10px;
}

@keyframes ych {
    0% {
        transform: translate(0, 0);
    }

    12.5% {
        transform: translate(0, 0);
    }

    25% {
        transform: translate(-350px, 0);
    }

    37.5% {
        transform: translate(-350px, 0);
    }

    50% {
        transform: translate(-700px, 0);
    }

    62.5% {
        transform: translate(-700px, 0);
    }

    75% {
        transform: translate(-1050px, 0);
    }

    87.5% {
        transform: translate(-1050px, 0);
    }

    100% {
        transform: translate(0, 0);
    }
}

.lbtbjs {
    width: 100%;
    height: 225px;
    background: red;
    border-radius: 15px;
    position: relative;
    top: -300px;
    z-index: -1;
}

.qqq {
    width: 100%;
    height: 100px;
    position: relative;
    top: -235px;
}

.qqq ul li {
    width: 123px;
    height: 100px;
    float: left;
}

.qqq ul li img {
    width: 100%;
    height: 100%;
}

.ann {
    width: 375px;
    height: 162px;
    position: relative;
    top: -235px;
}

.ann ul li {
    width: 73px;
    height: 73.95px;
    text-align: center;
    /* line-height: 73px; */
    float: left;
}

.ann ul li img {
    width: 39.98px;
    height: 39.98px;
}

.ann ul li span {
    width: 75px;
    height: 18px;
    margin-left: -20px;
}

.ann ol li {
    width: 73px;
    height: 73.95px;
    text-align: center;
    float: left;
    position: relative;
    top: -100px;
}

.jdms {
    width: 350px;
    height: 155px;
    position: relative;
    border-radius: 10px;
    top: -250px;
    left: 10px;
    background-color: white;
}

.jdms-top {
    width: 100%;
    height: 34px;
    background-size: contain;
    /* position: relative;
    top: -200px; */
}

.jdms-top img {
    width: 350px;
    height: 33px;
    position: relative;
    top: -133px;
}

.jdms-top-left {
    position: relative;
    top: -28px;
    left: 10px;
}

.jdms-top-left img {
    width: 68px;
    height: 18px;
}

.sd {
    width: 37px;
    height: 33px;
    position: relative;
    top: -180px;
    left: 85px;
    font-size: 12px;
    color: #232326;
    font-weight: 700;
    display: inline-block;
}

.djs {
    width: 72px;
    height: 16px;
    position: relative;
    top: -215px;
    left: 130px;
}

.djs div {
    width: 18px;
    height: 16px;
    border: 1px solid #ccc;
    color: black;
    float: left;
}

.djs span {
    float: left;
}

.xsms {
    position: relative;
    top: -230px;
    left: 200px;
    color: red;
}

.xsms i {
    display: inline-block;
    width: 11px;
    height: 11px;
    background: url(https://wq.360buyimg.com/wxsq_project/portal/m_jd_index/images/arrow_rt_2ccb8cd5.png) no-repeat;
    background-size: cover;
    position: absolute;
    right: -16px;
}

.tdtp {
    width: 350px;
    height: 120px;
}

.tdtp ul {
    width: 500px;
}

.tdtp ul li {
    width: 76px;
    height: 119px;
    float: left;
    position: relative;
    left: -63px;
    top: -190px;
    margin-left: 5px;
}

.tdtp .w1 {
    width: 76px;
    height: 66px;
}

.tdtp .w1 a {
    width: 66px;
    height: 66px;
    display: block;
    position: relative;
    left: 3px;
}

.tdtp .w1 a img {
    width: 100%;
    height: 100%;
}

.tdtp .w2 {
    width: 76px;
    height: 43px;
}

.tdtp .w2 em {
    width: 10px;
    height: 15px;
    color: red;
    font-size: 11px;
    position: relative;
    left: 16px;
    top: 7px;
}

.tdtp .w2 .w3 span {
    display: block;
    width: 27px;
    height: 19px;
    color: red;
    font-size: 16px;
    position: relative;
    left: 30px;
    top: -10px;
}

.tdtp .w2 .w4 {
    width: 30px;
    height: 19px;
    position: relative;
    left: 18px;
    top: -8px;
    color: gray;
}

.gg {
    width: 100%;
    height: 114px;
    position: relative;
    top: -430px;
}

.gg img {
    width: 100%;
    height: 100%;
}

.djxy img {
    width: 374px;
    height: 34px;
    position: relative;
    top: -317px;
}

.djxyx {
    width: 350px;
    height: 240px;
    position: relative;
    top: -320px;
    margin: 0 auto;
    border-radius: 10px;
    background-color: white;
}

.djxyx1 {
    width: 173px;
    height: 120px;
    float: left;
    position: relative;
    top: 5px;
    left: 5px;
}

.tss1 {
    width: 173px;
    height: 37px;
}

.tss1 span {
    background: -webkit-linear-gradient(left, #45CAFF, #1471FB);
    background: linear-gradient(90deg, #45CAFF, #1471FB);
    -webkit-background-clip: text;
    color: transparent;
    font-weight: 700;
    font-size: 18px;
    position: relative;
    left: 10px;
}

.tss1 p {
    position: relative;
    left: 10px;
}

.tss2 {
    width: 173px;
    height: 64px;
}

.tss2 .e1 {
    width: 59px;
    height: 59px;
    float: left;
    margin-left: 16px;
    margin-top: 3px;
}

.tss2 .e1 img {
    width: 100%;
    height: 100%;
}

.tss3 {
    width: 84px;
    height: 120px;
    float: left;
}

.tss3 img {
    width: 60px;
    height: 60px;
    position: relative;
    left: 11px;
    top: 10px;

}

.tss3 .e2 {
    font-size: 16px;
    position: relative;
    left: 10px;
}

.tss3 .e3 {
    font-size: 12px;
    position: relative;
    left: 10px;
}

.meg {
    width: 100%;
    height: 34px;
}

.meg img {
    width: 100%;
    height: 100%;
}

.mrg{
    width: 350px;
    height: 240px;
    margin: 240px auto;
    border: 1px solid;
}
.mrg .mrg1{
    width: 85px;
    height: 119px;
    border: 1px solid;
    float: left;
}
.mrg1 strong{
    background: -webkit-linear-gradient(left,#FF2A2A,#F139D2);
    background: linear-gradient(90deg, #FF2A2A,#F139D2);
    -webkit-background-clip: text;
    color: transparent;
}

.mrg .mrg1 img{
    width: 60px;
    height: 60px;
}
  </style>
</head>

<body>
    <div class="box">

        <div class="top">
            <div class="left">
                <div class="menu-icon" id="menu">
                    <span class="meny"></span>
                </div>
            </div>

            <div class="ssl">
                <input type="text" id="txt" placeholder="苹果笔记本" />
            </div>
            <div class="jdlogo">
                <span></span>
            </div>
            <div class="shuxian"></div>
            <div class="fdj"></div>

            <div class="dl">
                <span>登录</span>
            </div>
        </div>
        <div class="lbt">
            <div class="mais">
                <ul class="list">
                    <li><img
                            src="https://m.360buyimg.com/mobilecms/s700x280_jfs/t1/59558/7/9173/138616/5d6f2776E45677fc8/4b7fbfc25b60703b.jpg!cr_1125x445_0_171!q70.jpg.dpg">
                    </li>
                    <li><img
                            src="https://m.360buyimg.com/mobilecms/s700x280_jfs/t1/40591/19/14107/104442/5d7348ffE27700a67/d02ca91dbdb10f71.jpg!cr_1125x445_0_171!q70.jpg.dpg">
                    </li>
                    <li><img
                            src="https://imgcps.jd.com/ling4/4635062/5rC05p6c5LmQ5Lqr54uC5qyi/6LaF5L2O5Lu35qC8/p-5c11d16482acdd181dbc1fc5/4641100a/cr_1125x445_0_171/s1125x690/q70.jpg">
                    </li>
                    <li><img
                            src="https://m.360buyimg.com/mobilecms/s700x280_jfs/t1/48023/28/9906/123875/5d70faa6E9a4098db/83764d6694f033e9.jpg!cr_1125x445_0_171!q70.jpg.dpg">
                    </li>
                    <li><img
                            src="https://m.360buyimg.com/mobilecms/s700x280_jfs/t1/69738/11/10007/148537/5d7acdb6E887acd37/5cf05c1f23467c3d.jpg!cr_1125x445_0_171!q70.jpg.dpg">
                    </li>
                </ul>
            </div>
        </div>
        <div class="lbtbjs"></div>
        <div class="qqq">
            <ul>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s250x200_jfs/t1/76988/32/10046/100297/5d7a1856Ead4c2edc/55d9863a6b7cfded.png!q70.jpg.dpg">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s250x200_jfs/t1/72297/20/10211/48917/5d7a19c3E3e76fbc9/8f6cf0c727b34eca.png!q70.jpg.dpg">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s250x200_jfs/t1/67882/17/10067/34867/5d7a1e0eEc57dd601/6c866a879e438900.png!q70.jpg.dpg">
                </li>
            </ul>
        </div>
        <div class="ann">
            <ul>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t1/20983/16/10753/6124/5c8a16aaE5d6b15d7/01e0e818a7505267.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t1/39401/17/2391/5859/5cc06fcfE2ad40668/28cda0a571b4a576.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t1/17169/3/4127/4611/5c2f35cfEd87b0dd5/65c0cdc1362635fc.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t17725/156/1767366877/17404/f45d418b/5ad87bf0N66c5db7c.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t16990/157/2001547525/17770/a7b93378/5ae01befN2494769f.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t18454/342/2607665324/6406/273daced/5b03b74eN3541598d.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t22228/270/207441984/11564/88140ab7/5b03fae3N67f78fe3.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t1/7068/29/8987/5605/5c120da2Ecae1cc3a/016033c7ef3e0c6c.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t16828/63/2653634926/5662/d18f6fa1/5b03b779N5c0b196f.png.webp">
                </li>
                <li><img
                        src="https://m.360buyimg.com/mobilecms/s120x120_jfs/t1/22262/9/1470/4527/5c120cd0E5d3c6c66/4792ec307a853e9f.png.webp">
                </li>
            </ul>
            <ol>
                <li><span>京东超市</span></li>
                <li><span>数码电器</span></li>
                <li><span>京东服装</span></li>
                <li><span>京东生鲜</span></li>
                <li><span>京东到家</span></li>
                <li><span>充值缴费</span></li>
                <li><span>9.9元拼</span></li>
                <li><span>领劵</span></li>
                <li><span>赚钱</span></li>
                <li><span>PLUS会员</span></li>
            </ol>
        </div>
        <div class="jdms">
            <div class="jdms-top">
                <img
                    src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABYwAAACQBAMAAABZrTKvAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAYUExURUdwTO0PD+wQEOwVFewREekNDewQEOsQEC1iODQAAAAIdFJOUwB9YxIrs0VtoD6UjwAAA/1JREFUeNrt3cGO22QUBeAprsq2qSjdUks420gOsG0VK/sBjdiWEHnNmPeXsP94aIJEQExvmWt9n/oEZ46u72877s3NVa/vPrq9gZTOa3wnDnK6U2PUGJ7YUmE3Ro3h//LtWY1/FAc5fXdW45/EQU7Pzmr8Uhzk9Pysxu/EQfrl+GdhkH+rsFOQVvVwy+12IwzS+nKu8W+iILH3pcVfCYLU9q/vbn8VAwAAAAAAAJ/I88P9m+adHMjs+1XhQSqJvVjNPsiCrKq3DzV+tZEGSf2w+tPv0iDpML7/WOM3xjE5fbE68408SOmX8xp/LQ9S7hSrC7YKMnpxWeMPEiGhZ5c1fikREnp/WWM/7CX9Cc8Zj5zeXtb4lURI6P6yxm8kQkKrv5AI+WtsGmOpAEc8+G/ccGMBPP5gATyMZgG8GsQCeFGTxZ3xnPDIyY+YWMJW4SelLIAf+LOEcexzKyyAj1+xBD5FyBL4MCwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAkNtGBKQvcVvpMclV7UQOZG/xrt2Yx+ReKbbddtdWkiDxMK623WhnqyD1TtEVtmOS13g/1dhyTF7jZtwd97YKstd4P/XYNGYB07gzjUld4+PUY0sFdmOwG8NVVVVdfdD8cN/YNObp2pT3fjbXa2w15mnP4nZXJu2VkrZlHO+8G8TTncXj5lvOb5srTd9Oj6K1+HFJb8yBuGG87fpJd30cT7zh9qiLnle2I9Pt+sOhrqce/21NN9U/bM/8ixZ31y95PEK73ff1pDnurp3yKn+AR+ZcVjfzOGwY16ca90cRR+a8Hze3Y2czi5kS+0M99/ho4Ia1uCoXvWa85JkVIde6aRgPw9TjfqfGYcN4Xt16syIk324cxkO9Xq/HWdFJOCrm7XzROxzNipApMcY7dbhE7IIXetE7XfKE/OlNU2Jd1ophulchkKAad2UYj7tb76XtkBqfOrye9mM1jpwW80VPyBE723ixW0//hnLBk0jctFiXo7RLXlSNh3FMTNO46Xduakad8OoyjdemccyYKPfb6hKwhENjHoYSslkROI2n7dhSERpzWd0cQCKXtnU5RUs4cqkoB2khB+V7OAU8Tgqnj9BpMZwOIEIO0J7uG5d7QY3HH3E1Lg9LB9M4qMbdfENz3Np6D6MjYy5XvLrx+CPm8HEo71ScXg3S46CYu3J/fl033r8Kybc9Lcdevoo+g/ReDQq93PXzC8ee9odOCy9qhua7nWvce/cqclqM47iZWizkoB53/Vjkpul92yo25vlHTEKOmRPtww/8BRw6juevgYgiaq0YAz52fuwYHrMWx17vfEHhM8RcvvXh/ywODli+8TnLQMAAAADwWfwBKZghRTcFaz4AAAAASUVORK5CYII=">
                <div class="jdms-top-left">
                    <img
                        src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHEAAAAeCAMAAAAsAgFtAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAABpUExURUdwTAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPArMAAAAAAAAAAAAGQaGgAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPErMPYzNfEsMfErMPErMPEsMfIsMPEvMQAAAE7DusUAAAAidFJOUwA6wVQnRSzvC4r2cv77nuUFfhMwYq3ZzxogixNa37c2QymPBWCJAAADvklEQVRIx5WXiZKrIBBFUeOGBkFcYszK/3/k62Y3o6m8rqkKEdMHerkwhARLkqQie3ZKkgs5tJ6bT5llWfz7fufdD/9npZJdn51S+T6tyutZWde1UqqI5tI045uXL6LLfyNKpSjfey5S+Ik6JCrViRCbfDybhZfB4BfUfxEmnjikSp3L2CidcJIpbeeeCHgoNbGHkV32qCdHva2+mfQ3nFIHZvY/HMyyQBSV2d5iiCpkQO9KqalJGMWB3fGBy7PJMfu2HsEy8JTZgPI/RJ0579Bn9bRvi52VUgoINnwU1vS0S6slwsJKskMkpJgtsa7IzwbuxqO5QJx2iDxLNU3HtGSurGS9Z9E6oaKGXZxI0eGUjlgk6R/iUpeGJB05HfhxcTRBF+Db5Wjz2jokjp9EXapqHkw0C4vPfyCCo9m2V/OFWHtitzjZoAy74QTPAVsNs/ULxLnamoidw3tin5g3DZQ/awacE46Y2oB0U2OkwRIxXIyii8buIbImcn6B9zMsTyDXvpQjmRrMagZLZJy8X9q9V2VPBCU4GfdTsbU6Iu4GvYsmu14Tc69yr/apYxNrmR/nhvgtj+Oh5KAG6grkGPkEiRRSeG3b1ebxQFi+Eyt6LIF8dnwYLEDsEsIfbXsnh8RULzRzBkkR8DGgSX8eOcPKcWPbj7Bm/JsIyDQn9XwhKwDbhymT3BqG3o1PP56P5Kg78FgRFIkllG6ld9i214/zPKoc05se7YgyWswCY7khhidMaSXPZ4jgZHUNkW8dG1SuKib6JyhA2YYoQm3oAqw3xFy5dmLM6KoEIcQEva438nZbRKmatnvEIzIxGbZHkyOeXIptqSYbIocCpSaPlVPyEmoGuuLePtf7LTSO2BJxJ9C9lfJHg8/jFDouDH0emRNa7s+OGYXt8eDta12JLyslt0RpFlEofzR4ovC55mcX1EDMVKgwS6zI+wmNeL+H69DoghpVzqQ3l+mLypYo/fqWcPh4IrbosCWS5/1K1ut1JbEc159Ecyg0IWehOyZXTFAmJf/sjtE7c8QbVOhte90rnbN+DEqOVwXMinFUpCFatct646q2Z0GIsnApoKo8aWGDvl8312aX/wWVsOP+4tvj0i9uh2q++FOYOXTudogiZsJ69qcNnY2Stq5Eo3O89hliVei1BLA2qJBPwcMtPLUBtEEFIutDVVA3qoywXdcPhcoodTURLuI8oTSDfzbstU3NRfyfhqkcmdiHaZeF2SUJarjeYYOvY3GU7PASJ/i3C13TH0w8b7cbJ/9h/wCzsZRNJjJk+QAAAABJRU5ErkJggg==">
                </div>
                <strong class="sd">
                    14点场
                </strong>
                <div class="djs">
                    <div>0-1</div>
                    <span>:</span>
                    <div>0-1</div>
                    <span>:</span>
                    <div>0-2</div>
                </div>
                <a class="xsms">更多秒杀<i></i></a>
            </div>
            <div class="tdtp">
                <ul>
                    <li>
                        <div class="w1"><a><img
                                    src="https://img14.360buyimg.com/n1/s150x150_jfs/t1/76708/4/9660/82079/5d75fa1eEee515ba2/5a650cdf6af53bf2.jpg.dpg"></a>
                        </div>
                        <div class="w2">
                            <span class="w3">
                                <em>￥</em>
                                <span>468</span>
                            </span>
                            <span class="w4">￥1899</span>
                        </div>
                    </li>
                    <li>
                        <div class="w1"><a><img
                                    src="https://img14.360buyimg.com/n1/s150x150_jfs/t1/70707/14/9509/184063/5d7211e3E138f5e62/18c78d254a04f092.jpg.dpg"></a>
                        </div>
                        <div class="w2">
                            <span class="w3">
                                <em>￥</em>
                                <span>39</span>
                            </span>
                            <span class="w4">￥109</span>
                        </div>
                    </li>
                    <li>
                        <div class="w1"><a><img
                                    src="https://img14.360buyimg.com/n1/s150x150_jfs/t18964/123/934396551/258642/78148bb9/5ab1f4f5N5ff90f65.jpg.dpg"></a>
                        </div>
                        <div class="w2">
                            <span class="w3">
                                <em>￥</em>
                                <span>489</span>
                            </span>
                            <span class="w4">￥1999</span>
                        </div>
                    </li>
                    <li>
                        <div class="w1"><a><img
                                    src="https://img14.360buyimg.com/n1/s150x150_jfs/t1/60404/16/9914/201832/5d787b6fE5dc7661b/6dd271a8bfee0637.png.webp"></a>
                        </div>
                        <div class="w2">
                            <span class="w3">
                                <em>￥</em>
                                <span>6.9</span>
                            </span>
                            <span class="w4">￥96</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
        <div class="gg">
            <img
                src="https://m.360buyimg.com/mobilecms/s750x230_jfs/t1/64531/25/10074/127692/5d79e47dE40916c18/1f79a5f6c492d9cd.jpg!q70.jpg.dpg">
        </div>
        <div class="djxy">
            <img
                src="https://m.360buyimg.com/mobilecms/s750x80_jfs/t1/80458/35/2250/24646/5d09044cEb3c6b467/e1af43a6ea0cb5fa.png!q70.jpg.dpg">
        </div>
        <div class="djxyx">

            <div class="djxyx1">
                <div class="tss1">
                    <span>轻松上分</span>
                    <p>王者吃鸡开黑</p>
                </div>
                <div class="tss2">
                    <div class="e1"><img
                            src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/83439/20/3492/44769/5d1b164aE23181163/bddfb490026d9dcd.jpg!q70.jpg.dpg">
                    </div>
                    <div class="e1"><img
                            src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/76898/38/5958/175292/5d428e7bEe43df5a1/8cdffb5f8fc36c88.jpg!q70.jpg.dpg">
                    </div>
                </div>
            </div>

            <div class="djxyx1">
                <div class="tss1">
                    <span>意试家具</span>
                    <p>极简主义的生活方式</p>
                </div>
                <div class="tss2">
                    <div class="e1"><img
                            src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/64170/5/9818/253013/5d779aacE5cad197a/1815224fdec11cbf.jpg!q70.jpg.dpg">
                    </div>
                    <div class="e1"><img
                            src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/63095/29/9893/236697/5d779ab0E01bb2064/411344a79af1c77e.jpg!q70.jpg.dpg">
                    </div>
                </div>
            </div>

            <div class="djxyx1">
                <div class="tss3">
                    <strong class="e2">好物必败</strong>
                    <p class="e3">不止好看</p>
                    <img
                        src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/39251/39/10582/193374/5d1dcdb9Ebec3098c/9ab4794fe9682a77.jpg!q70.jpg.dpg">
                </div>
                <div class="tss3">
                    <strong class="e2">流行美妆</strong>
                    <p class="e3">优雅又吸睛</p>
                    <img
                        src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/70409/11/6957/138004/5d5109e1E37bf2fb9/4896271b14220073.jpg!q70.jpg.dpg">
                </div>
            </div>

            <div class="djxyx1">
                <div class="tss3">
                    <strong class="e2">净爽剃须</strong>
                    <p class="e3">男神同款</p>
                    <img
                        src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/56457/19/7912/129214/5d5673b5Ec46445bc/a4bd2ffce3090264.jpg!q70.jpg.dpg">
                </div>
                <div class="tss3">
                    <strong class="e2">呵护宝贝</strong>
                    <p class="e3">妈妈放心</p>
                    <img
                        src="https://m.360buyimg.com/mobilecms/s150x150_jfs/t1/71215/39/5259/186414/5d37f58eEc4c0d693/3a46758f3cbb664f.jpg!q70.jpg.dpg">
                </div>
            </div>
            <div class="meg">
                <img
                    src="https://m.360buyimg.com/mobilecms/s750x80_jfs/t1/39486/28/9224/23804/5d09048aE5127de40/eec779757a34e94d.png!q70.jpg.dpg">
            </div>

            <div class="mrg">
                <div class="mrg1">
                    <strong>免息星球</strong>
                    <p>白条免息购</p>
                    <img src="https://m.360buyimg.com/n1/s150x150_jfs/t29566/227/1464891645/10350/a5b133e2/5ce20cdcNd9cdd972.jpg!q70.jpg.dpg">
                </div>
                <div class="mrg1"></div>
                <div class="mrg1"></div>
                <div class="mrg1"></div>
                <div class="mrg1"></div>
                <div class="mrg1"></div>
                <div class="mrg1"></div>
                <div class="mrg1"></div>
            </div>

        </div>

    </div>
