# my-web
<h2 id="sapaan"></h2>

<script>
  const jam = new Date().getHours();
  let teks;

  if (jam < 12) {
    teks = "Selamat Pagi! Siap beraktivitas?";
  } else if (jam < 18) {
    teks = "Selamat Siang! Terima kasih sudah berkunjung.";
  } else {
    teks = "Selamat Malam! Selamat beristirahat sambil menjelajah.";
  }

  document.getElementById("sapaan").innerText = teks;
</script>
