<!DOCTYPE html>

<div id="HeadBar"></div>

  <!--League Logo Linked to Website-->
  <a href="http://na.leagueoflegends.com/en">
    <img id="Symbol" src="http://vignette1.wikia.nocookie.net/leagueoflegends/images/8/86/League_of_legends_logo_transparent.png/revision/latest/scale-to-width-down/640?cb=20131023175853">
  </a>

  <!--Input for Summoner Name and Champion Name-->
  <div id="NameEnter">
    <span>aaa</span><b>Summoner Name</b>
    <br>
    <input id="SumName" />
  </div>

  <div id="ChampEnter">
    <span>aaal</span><b>Champion Name</b>
    <br>
    <input id="ChampName" />
    <input id="Search" type="submit" onclick="summonerLookUp();" />
  </div>



<!--Champion Squares on Main Page-->
  <div id="ChampList">
  <table id="ChampDirec">
    <tr>
      <td>
      Enter Champion Name Into Search Box Exactly As Shown Below Picture
    </td>
    </tr>
    </table>
    <table id="ChampSquares">

      <tr>
<br><br><br>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=266"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Aatrox.png" alt=""></a>
          Aatrox
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=103"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Ahri.png" alt=""></a>
          Ahri
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=84"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Akali.png" alt=""></a>
          Akali
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=12"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Alistar.png" alt=""></a>
          Alistar
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=32"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Amumu.png" alt=""></a>
          Amumu
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=34"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Anivia.png" alt=""></a>
          Anivia
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=1"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Annie.png" alt=""></a>
          Annie
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=22"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Ashe.png" alt=""></a>
          Ashe
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=268"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Azir.png" alt=""></a>
          Azir
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=432"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Bard.png" alt=""></a>
          Bard
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=53"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Blitzcrank.png" alt=""></a>
          Blitzcrank
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=63"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Brand.png" alt=""></a>
          Brand
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=201"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Braum.png" alt=""></a>
          Braum
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=51"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Caitlyn.png" alt=""></a>
          Caitlyn
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=69"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Cassiopeia.png" alt=""></a>
          Cassiopeia
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=31"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Chogath.png" alt=""></a>
          Chogath
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=42"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Corki.png" alt=""></a>
          Corki
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=122"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Darius.png" alt=""></a>
          Darius
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=131"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Diana.png" alt=""></a>
          Diana
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=36"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/DrMundo.png" alt=""></a>
          Dr.Mundo
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=119"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Draven.png" alt=""></a>
          Draven
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=245"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Ekko.png" alt=""></a>
          Ekko
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=60"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Elise.png" alt=""></a>
          Elise
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=28"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Evelynn.png" alt=""></a>
          Evelynn
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=81"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Ezreal.png" alt=""></a>
          Ezreal
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=9"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/FiddleSticks.png" alt=""></a>
          Fiddlesticks
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=114"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Fiora.png" alt=""></a>
          Fiora
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=105"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Fizz.png" alt=""></a>
          Fizz
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=3"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Galio.png" alt=""></a>
          Galio
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=86"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Garen.png" alt=""></a>
          Garen
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=150"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Gnar.png" alt=""></a>
          Gnar
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=79"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Gragas.png" alt=""></a>
          Gragas
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=104"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Graves.png" alt=""></a>
          Graves
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=120"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Hecarim.png" alt=""></a>
          Hecarim
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=74"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Heimerdinger.png" alt=""></a>
          Heimerdinger
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=39"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Irelia.png" alt=""></a>
          Irelia
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=40"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Janna.png" alt=""></a>
          Janna
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=59"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/JarvanIV.png" alt=""></a>
          Jarvan IV
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=24"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Jax.png" alt=""></a>
          Jax
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=126"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Jayce.png" alt=""></a>
          Jayce
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=222"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Jinx.png" alt=""></a>
          Jinx
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=429"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Kalista.png" alt=""></a>
          Kalista
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=43"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Karma.png" alt=""></a>
          Karma
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=30"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Karthus.png" alt=""></a>
          Karthus
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=38"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Kassadin.png" alt=""></a>
          Kassadin
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=55"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Katarina.png" alt=""></a>
          Katarina
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=10"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Kayle.png" alt=""></a>
          Kayle
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=85"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Kennen.png" alt=""></a>
          Kennen
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=121"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Khazix.png" alt=""></a>
          Kha'Zix
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=96"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/KogMaw.png" alt=""></a>
          Kog'Maw
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=7"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Leblanc.png" alt=""></a>
          LeBlanc
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=64"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/LeeSin.png" alt=""></a>
          Lee Sin
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=89"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Leona.png" alt=""></a>
          Leona
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=127"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Lissandra.png" alt=""></a>
          Lissandra
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=236"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Lucian.png" alt=""></a>
          Lucian
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=117"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Lulu.png" alt=""></a>
          Lulu
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=99"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Lux.png" alt=""></a>
          Lux
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=54"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Malphite.png" alt=""></a>
          Malphite
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=90"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Malzahar.png" alt=""></a>
          Malzahar
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=57"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Maokai.png" alt=""></a>
          Maokai
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=11"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/MasterYi.png" alt=""></a>
          Master Yi
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=21"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/MissFortune.png" alt=""></a>
          Miss Fortune
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=82"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Mordekaiser.png" alt=""></a>
          Mordekaiser
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=25"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Morgana.png" alt=""></a>
          Morgana
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=267"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Nami.png" alt=""></a>
          Nami
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=75"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Nasus.png" alt=""></a>
          Nasus
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=111"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Nautilus.png" alt=""></a>
          Nautilus
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=76"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Nidalee.png" alt=""></a>
          Nidalee
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=56"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Nocturne.png" alt=""></a>
          Nocturne
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=20"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Nunu.png" alt=""></a>
          Nunu
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=2"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Olaf.png" alt=""></a>
          Olaf
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=61"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Orianna.png" alt=""></a>
          Orianna
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=80"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Pantheon.png" alt=""></a>
          Pantheon
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=78"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Poppy.png" alt=""></a>
          Poppy
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=133"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Quinn.png" alt=""></a>
          Quinn
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=33"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Rammus.png" alt=""></a>
          Rammus
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=421"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/RekSai.png" alt=""></a>
          Rek'Sai
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=58"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Renekton.png" alt=""></a>
          Renekton
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=107"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Rengar.png" alt=""></a>
          Rengar
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=92"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Riven.png" alt=""></a>
          Riven
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=68"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Rumble.png" alt=""></a>
          Rumble
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=13"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Ryze.png" alt=""></a>
          Ryze
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=113"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Sejuani.png" alt=""></a>
          Sejuani
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=35"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Shaco.png" alt=""></a>
          Shaco
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=98"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Shen.png" alt=""></a>
          Shen
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=102"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Shyvana.png" alt=""></a>
          Shyvana
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=27"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Singed.png" alt=""></a>
          Singed
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=14"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Sion.png" alt=""></a>
          Sion
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=15"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Sivir.png" alt=""></a>
          Sivir
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=72"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Skarner.png" alt=""></a>
          Skarner
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=37"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Sona.png" alt=""></a>
          Sona
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=16"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Soraka.png" alt=""></a>
          Soraka
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=50"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Swain.png" alt=""></a>
          Swain
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=134"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Syndra.png" alt=""></a>
          Syndra
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=223"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/TahmKench.png" alt=""></a>
          Tahm Kench
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=91"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Talon.png" alt=""></a>
          Talon
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=44"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Taric.png" alt=""></a>
          Taric
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=17"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Teemo.png" alt=""></a>
          Teemo
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=412"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Thresh.png" alt=""></a>
          Thresh
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=18"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Tristana.png" alt=""></a>
          Tristana
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=48"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Trundle.png" alt=""></a>
          Trundle
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=23"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Tryndamere.png" alt=""></a>
          Tryndamere
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=4"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/TwistedFate.png" alt=""></a>
          Twisted Fate
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=29"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Twitch.png" alt=""></a>
          Twitch
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=77"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Udyr.png" alt=""></a>
          Udyr
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=6"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Urgot.png" alt=""></a>
          Urgot
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=110"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Varus.png" alt=""></a>
          Varus
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=67"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Vayne.png" alt=""></a>
          Vayne
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=45"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Veigar.png" alt=""></a>
          Veigar
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=161"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Velkoz.png" alt=""></a>
          Vel'Koz
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=254"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Vi.png" alt=""></a>
          Vi
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=112"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Viktor.png" alt=""></a>
          Viktor
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=8"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Vladimir.png" alt=""></a>
          Vladmir
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=106"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Volibear.png" alt=""></a>
          Volibear
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=19"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Warwick.png" alt=""></a>
          Warwick
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=62"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/MonkeyKing.png" alt=""></a>
          Wukong
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=101"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Xerath.png" alt=""></a>
          Xerath
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=5"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/XinZhao.png" alt=""></a>
          Xin Zhao
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=157"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Yasuo.png" alt=""></a>
          Yasuo
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=83"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Yorick.png" alt=""></a>
          Yorick
        </td>
      </tr>

      <tr>
        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=154"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Zac.png" alt=""></a>
          Zac
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=238"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Zed.png" alt=""></a>
          Zed
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=115"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Ziggs.png" alt=""></a>
          Ziggs
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=26"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Zilean.png" alt=""></a>
          Zilean
        </td>

        <td class="champSq">
          <a href="http://ehco.planet.ee/BMB/champions.php?id=143"><img src="http://ddragon.leagueoflegends.com/cdn/5.16.1/img/champion/Zyra.png" alt=""></a>
          Zyra
        </td>

      </tr>
    </table>
    </div>
      

