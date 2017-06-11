# Đăng kí
## Luôn miễn phí
<title>btvn</title>
<script>
var a = document.forms["create"]["fname"].value;
var b = document.forms["create"]["lname"].value;
var c = document.forms["create"]["sdtoremail"].value;
var d = document.forms["create"]["password"].value;
var e = document.forms["create"]["bday"].value;
var f = document.forms["create"]["bmonth"].value;
var g = document.forms["create"]["byear"].value;
var h = document.forms["create"]["gender"].value;
fname = document.forms["create"]["fname"].value;
lname = document.forms["create"]["lname"].value;
sdtoremail = document.forms["create"]["sdtoremail"].value;
password = document.forms["create"]["password"].value;
bday = document.forms["create"]["bday"].value;
bmonth = document.forms["create"]["bmonth"].value;
byear = document.forms["create"]["byear"].value;
gender = document.forms["create"]["gender"].value;
cond1 = fname != null;
cond2 = lname != null;
cond3 = sdtoremail != null;
cond4 = password != null;
cond5 = bday != null;
cond6 = bmonth != null;
cond7 = byear != null;
cond8 = gender != null;
if(cond1 && cond2 && cond3 && cond4 && cond5 && cond6 && cond7 && cond8){
	alert("da nhap du");
} else {
	if(cond1){
		alert("chua nhap fname");
	}

	if(cond2){
		alert("chua nhap lname");
	}
	if(cond3){
		alert("chua nhap sdtoremail");
	}
	if(cond4){
		alert("chua nhap password");
	}
	if(cond5){
		alert("chua nhap bday");
	}
	if(cond6){
		alert("chua nhap bmonth");
	}
	if(cond7){
		alert("chua nhap byear");
	}
	if(cond8){
		alert("chua nhap gender");
	}
</script>
<form name="create" onsubmit="return checkinformation()">
<input type="text" name="fname" placeholder="Họ"> 
<input type="text" name="lname" placeholder="Tên"><br><br>
<input type="text" name="sdtoremail" placeholder="Số di dộng hoặc email"><br><br>
<input type="password" name="password" placeholder="Mật khẩu mới"><br>
Ngày sinh:
<br>
<select name="bday" >
	<option value="" selected>ngày</option>
	<option value="1">1</option>
	<option value="2">2</option>
	<option value="3">3</option>
	<option value="4">4</option>
	<option value="5">5</option>
	<option value="6">6</option>
	<option value="7">7</option>
	<option value="8">8</option>
	<option value="9">9</option>
	<option value="10">10</option>
	<option value="11">11</option>
	<option value="12">12</option>
	<option value="13">13</option>
	<option value="14">14</option>
	<option value="15">15</option>
	<option value="16">16</option>
	<option value="17">17</option>
	<option value="18">18</option>
	<option value="19">19</option>
	<option value="20">20</option>
	<option value="21">21</option>
	<option value="22">22</option>
	<option value="23">23</option>
	<option value="24">24</option>
	<option value="25">25</option>
	<option value="26">26</option>
	<option value="27">27</option>
	<option value="28">28</option>
	<option value="29">29</option>
	<option value="30">30</option>
	<option value="31">31</option>
</select>	
<select name="bmonth">
	<option value="" selected> tháng </option>
	<option value="1">1</option>
	<option value="2">2</option>
	<option value="3">3</option>
	<option value="4">4</option>
	<option value="5">5</option>
	<option value="6">6</option>
	<option value="7">7</option>
	<option value="8">8</option>
	<option value="9">9</option>
	<option value="10">10</option>
	<option value="11">11</option>
	<option value="12">12</option>
</select>
<select name="byear">
	<option value="" selected> năm </option>
	<option value="2017">2017</option>
	<option value="2016">2016</option>
	<option value="2015">2015</option>
	<option value="2014">2014</option>
	<option value="2013">2013</option>
	<option value="2012">2012</option>
	<option value="2011">2011</option>
	<option value="2010">2010</option>
	<option value="2009">2009</option>
	<option value="2008">2008</option>
	<option value="2007">2007</option>
	<option value="2006">2006</option>
	<option value="2005">2005</option>
	<option value="2004">2004</option>
	<option value="2003">2003</option>
	<option value="2002">2002</option>
	<option value="2001">2001</option>
	<option value="2000">2000</option>
	<option value="1999">1999</option>
	<option value="1997">1997</option>
	<option value="1996">1996</option>
	<option value="1995">1995</option>
	<option value="1994">1994</option>
	<option value="1993">1993</option>
	<option value="1992">1992</option>
	<option value="1991">1991</option>
	<option value="1990">1990</option>
	<option value="1989">1989</option>
	<option value="1988">1988</option>
	<option value="1987">1987</option>
	<option value="1986">1986</option>
	<option value="1985">1985</option>
	<option value="1984">1984</option>
	<option value="1983">1983</option>
	<option value="1982">1982</option>
	<option value="1981">1981</option>
	<option value="1980">1980</option>
	<option value="1979">1979</option>
	<option value="1978">1978</option>
	<option value="1977">1977</option>
	<option value="1976">1976</option>
	<option value="1975">1975</option>
	<option value="1974">1974</option>
	<option value="1973">1973</option>
	<option value="1972">1972</option>
	<option value="1971">1971</option>
	<option value="1970">1970</option>
	<option value="1969">1969</option>
	<option value="1968">1968</option>
	<option value="1967">1967</option>
	<option value="1966">1966</option>
	<option value="1965">1965</option>
	<option value="1964">1964</option>
	<option value="1963">1963</option>
	<option value="1962">1962</option>
	<option value="1961">1961</option>
	<option value="1960">1960</option>
	<option value="1959">1959</option>
	<option value="1958">1958</option>
	<option value="1957">1957</option>
	<option value="1956">1956</option>
	<option value="1955">1955</option>
	<option value="1954">1954</option>
	<option value="1953">1953</option>
	<option value="1952">1952</option>
	<option value="1951">1951</option>
	<option value="1950">1950</option>
	<option value="1949">1949</option>
	<option value="1948">1948</option>
	<option value="1947">1947</option>
	<option value="1946">1946</option>
	<option value="1945">1945</option>
	<option value="1944">1944</option>
	<option value="1943">1943</option>
	<option value="1942">1942</option>
</select><br><br>
<input type="radio" name="gender" value="Nữ" >Nữ<br>
<input type="radio" name="gender" value="Nam">Nam<br>
<input id="button!" type="submit" name="submited" value="Tạo tài khoản" >
</form>
