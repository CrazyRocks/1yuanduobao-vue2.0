<template>
    <section class="mainbody">
        <article class="qa-detail">
            <dl>
                <dt>
                    <span>问</span>
                    <div id="wen"></div>
                </dt>
                <dd>
                    <span>答</span>
                    <p id="da"></p>
                </dd>
            </dl>
        </article>

    </section>
</template>
<script>
var qadata = {
                'q1': ['疯狂夺宝提醒您：保护自身利益，避免损失','（1）各种形式的合购、合资、私下交易等都具有极高的风险，请大家切勿参与；<br>（2）凡以“高中奖率、内部员工、系统存在漏洞”等信息进行代购的，均属欺诈行为；<br> （3）疯狂夺宝官方工作人员在任何时候都不会向用户索取账户密码等信息，请大家注意保护自己的信息安全； <br>（4）当您获得商品之后，我们不会以私信或者QQ私聊等形式通知您获得商品，更不会以任何理由要求您缴纳任何其他费用； <br>（5）如有疑问请第一时间联系疯狂夺宝在线客服，客服工作时间为9点至18点。'],
                'q2': ['夺宝获得的商品什么时候发货','获得夺宝商品后请您尽快提交收货地址，超过7天未确认收货地址，视为自动放弃该商品（系统不会默认您的“收货地址”中的地址信息，每次获得夺宝商品后都需要确认收货地址）。虚拟商品如:（话费,Q币等）会在3个工作日内充值，个别用户充值后没有短信，建议拨打相关咨询电话咨询如(10086、10010、10000)。快递托运的商品会在7个工作日内发货。（工作日是指除周末、法定节假日的工作时间）'],
                'q3': ['商品是正品吗','夺宝所有商品均由我们公司确认的第三方商家提供及发货，100%正品，可享受厂家所提供的全国联保服务。'],
                'q4': ['夺宝获得的商品如何保修', '夺宝所有商品均从正规渠道采购，100%正品，可享受厂家所提供的全国联保服务。售后标准均依照该产品的售后标准进行。（如遇到产品质量问题，建议第一时间联系该产品的官方指定售后维修点；）'],
                'q5': ['我可以修改已确认的收货地址吗','获得夺宝商品后一旦确认收货地址，无法二次修改。请您慎重填写！ 如因用户个人原因，导致快递无法正常派发，二次寄送则由用户自行承担物流运输费用。'],
                'q6': ['夺宝是公正的吗', '公平、公正是疯狂夺宝赖以生存的根本。夺宝的幸运号码由公式计算得出，公式中的两个数字都是不受人为干扰的。由于使用了“老时时彩”开奖结果作为参数，因此幸运号码肯定是未知的；<br>（1）商品的最后一个号码分配完毕后，将公示该分配时间点前本站全部商品的最后50个参与时间； <br>（2）将这50个时间的数值进行求和（得出数值A）（每个时间按时、分、秒、毫秒的顺序组合，如20:15:25.362则为201525362）； <br>（3）为保证公平公正公开，系统还会等待一小段时间，取最近下一期中国福利彩票“老时时彩”的开奖结果（一个五位数值B）； <br>（4）（数值A+数值B）除以该商品总需人次得到的余数 + 原始数 10000001，得到最终幸运号码，拥有该幸运号码者，直接获得该商品。 注：如遇福彩中心通讯故障，无法获取上述期数的中国福利彩票“老时时彩”开奖结果，且24小时内该期“老时时彩”开奖结果仍未公布，则默认“老时时彩”开奖结果为00000。'],
                'q7': ['可以挑选夺宝商品的颜色或型号吗', '用户获得的夺宝商品按参与夺宝时的商品名称来寄送，颜色型号等均不能挑选或者更改。'],
                'q8': ['支付出现问题应该如何处理', '网上支付未及时到帐可能有以下几个原因造成： <br>（1）由于网速或者支付接口等问题，支付数据没有及时传送到支付系统造成的； <br>（2）网速过慢，数据传输超时使银行后台支付信息不能成功对接，导致银行交易成功而支付后台显示失败； <br>（3）如果使用某些防火墙软件，有时会屏蔽银行接口的弹出窗口。 <br>如果支付过程问题遇到问题，请与我们联系。']
        }
    var hash = document.location.hash;

    hash = hash.replace('#', '');

    var wen = qadata[hash][0];
    var da = qadata[hash][1];

    document.querySelector('#wen').innerHTML = wen;

    document.querySelector('#da').innerHTML = da;

</script>


