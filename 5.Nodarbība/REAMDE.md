<!DOCTYPE html>
<html>
<body>
<title>Mana anketa</title>
<link type="image/png" sizes="16x16" rel="icon" href="">
<body style="background-color:rgb(216, 162, 14);"> </body>
<h2>Kaut kāda anketa</h2>

<form action="/action_page.php">
  <label for="fname">Vārds:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Uzvārds:</label><br>
  <input type="text" id="lname" name="lname"><br><br>
  <input type="submit" value="Ai daivai nosūti">

  </Form>
  
  <p> <h2>Esi cilvēks?</h2></p>
  
  <form action="/action_page.php">
    <input type="checkbox" id="jā" name="jā" value=tieši 100% humanoīds>
    <label for="jā"> 100% humanoīds</label><br>
     <input value=""> 
    <p>
    <input type="checkbox" id="nē" name="nē" value=kas par jautājumu>
    <lable for="jā"> absolūts tironozaurs</label><br>
    <input value="">
    </p>

<form action="/action_page.php">
<input type="submit" value="Še, saņem">
</form> 

<h3> Kur tu dzīvo</h3>
<form action="/action_page.php">
  <label for="cars">Izvēlies pilsētu:</label>
  <select id="cars" name="cars">
     <option value="Jelgava">Jelgava</Option>
        <option value="Mītava">Mītava</Option>
        <option value="Rīga">Rīga</Option>
        <option value="Liepāja">Liepāja</Option>
        <option value="Ventspils">Ventspils</Option>
        <option value="Jēkabpils">Jēkabpis</Option>
        <option value="Redneck paradise">Redneck paradise</Option>
  </select>
  <input type="submit" value="pieņem">
</form>

<p> <h3> pasaki to man </h3> <p>

<form actiona="action_page.php">
    <textarea name="message"  rows="13" cols="13"></textarea>
    <br><br>
    <input type="submit" value="saņem">
    </form>

<p> <h3>un te tu paraksties </h3> <p>
<form action="/action_page.php">
    <label fro="email">Neēsi sēne - ieliec epastu: </label>
    <input type="email" id="email" name="email">
    <input type="submit" value="nosūtīt">
    </form>

<p> <form action="/action_page.php">
    <label fro="files">Izvēlies ko vēlies: </label>
    <input type="file" id="files" name="files">
    <input type="submit" value="nosūtīt">
    </form> </p>

<p> <h1> datums </h2> <p>
<form action="/action_page.php">
    <label for="datemax">ievadi datumu</label>
    <input type="date" id="date" name="date" max="2022-12-31"><br><br>
    <input type="submit" value="nosūtīt">

<p>Ja nosūtīsi, tu piekrīti un paraksties uz mūsu nosacījumiem</p>

</body>
</html>


