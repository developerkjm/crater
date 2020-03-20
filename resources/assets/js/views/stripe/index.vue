<template>

<!--  <div class="page">
    <iframe src="https://8098e554.ngrok.io" frameborder="0" style="display:block; width:100vw; height: 100vh"></iframe>
  </div>-->


<form action="http://api2.stg.paymentapi.co:8081/payment2.php" method="post">

	loginname<input type="text" name="loginname" value="sang4"><br>
	charge_type<input type="text" name="charge_type" value="6"><br>
	site_id<input type="text" name="site_id" value="258"><br>
	token<input type="text" name="token" value="2c4b4545a9b80dbac64f490f48cceca4"><br>
	email<input type="text" name="email" value="your@emailaddresshere.com"><br>
	firstname<input type="text" name="firstname" value="Taro"><br>
	lastname<input type="text" name="lastname" value="Yamada"><br>
	usrtel<input type="text" name="usrtel" value="0312345555"><br>
	cardnumber<input type="text" name="cardnumber" value=""><br>
	cardmonth<input type="text" name="cardmonth" value="03"><br>
	cardyear<input type="text" name="cardyear" value="2020"><br>
	cvv<input type="text" name="cvv" value="999"><br>
	currency<input type="text" name="currency" value="JPY"><br>
	customer_id[0]<input type="text" name="customer_id[0]" value="789"><br>
	contents_id[0]<input type="text" name="contents_id[0]" value="98765432"><br>
	contents_name[0]<input type="text" name="contents_name[0]" value="サービス名"><br>
	amount[0]<input type="text" name="amount[0]" value="1980"><br>
	<input type="submit" value="Submit">

	<!-- password: sang4123-->

</form>


</template>
<script >

</script>