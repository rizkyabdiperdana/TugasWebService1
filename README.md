# TugasWebService1

<!DOCTYPE html>
<html>
<head>
<title>Daftar Buku</title>
<!--Bagian CSS untuk Styling Tabel-->
<style type="text/css">
          table, th, td
          {
               border: 1px solid black;
          }
</style>
</head>
<body>
 
<h3>Daftar Buku Terbaru</h3>
<?php
// untuk meload data xml (buku.xml) dengan cara SimpleXML 
$books = new SimpleXMLElement('buku.xml', null, true);
 
// menampilkan data ke XML ke dalam tabel HTML
echo "
<table>
<tr>
<th>Judul</th>
<th>Pengarang</th>
<th>Penerbit</th>
<th>Harga</th>
<th>ISBN</th>
</tr>
 
";
 
// melakukan looping penampilan data buku
foreach($books as $buku)
{
        echo "
<tr>
<td width='200'>{$buku->judul}</td>
<td width='200'>{$buku->pengarang}</td>
<td width='130'>{$buku->penerbit}</td>
<td width='80'>\${$buku->harga}</td>
<td width='130'>{$buku['isbn']}</td>
</tr>
 
";
}
echo '</table>';
?>
 
</body>
</html>
