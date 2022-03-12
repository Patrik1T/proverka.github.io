<!DOCTYPE html>
<html lang="cs">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="../css/style.css" />
    <title>Priprava na praktickou prověrku</title>
  </head>
  <body>
    <header>
      <h1>Priprava na praktickou proverku</h1>
    </header>
     <main>
      <ul>
      <li><a href="#s1">Textove upravy</a></li>
      <li><a href="#s2">Tabulka</a></li>
      </ul>
      <h2 id="s1">Textove upravy</h2>
      <h3>Adresy pouzivane na internetu</h3>
      <p>
        <b>IP adresa</b> je v informatice číslo, které jednoznačně identifikuje
        síťové rozhraní v počítačové síti, která používá IP protokol. V současné
        době je nejrozšířenější <b>IPv4</b>, která používá 32bitové IP adresy,
        které jsou zapisovány dekadicky po jednotlivých oktetech (tj. po
        osmicích bitů), například 192.168.0.2. Z důvodu nedostatku adres je IPv4
        postupně nahrazován protokolem <b>IPv6</b>, který používá 128bitové IP
        adresy zapsané hexadecimálně
      </p>
      <h3>Seznam vyznamnych terminu a zkratek</h3>
      <h4>HTML</h4>
      <p>
        First developed by Tim Berners-Lee in 1990, HTML is short for Hypertext
        Markup Language. HTML is used to create electronic documents (called
        pages) that are displayed on the World Wide Web. Each page contains a
        series of connections to other pages called hyperlinks. Every web page
        you see was written using one version of HTML.
      </p>
      <h4>HTTP</h4>
      <p>
        HTTP means <b>HyperText Transfer Protocol</b>. HTTP is the underlying
        protocol used by the World Wide Web. Developed by Tim Berners-Lee, HTTP
        defines how messages are formatted and transmitted, and what actions Web
        servers and browsers should take in response to various commands.
      </p>
      <h4>Validation</h4>
      <p>
        Validation is an automatic computer check to ensure that the data
        entered is sensible and reasonable. It does not check the accuracy of
        data.
      </p>
      <h4>Server</h4>
      <p>
        A server is a computer, a device or a program that is dedicated to
        managing network resources. They are called that because they “serve”
        another computer, device, or program called “client” to which they
        provide functionality. There are a number of categories of servers,
        including print servers, file servers, network servers and database
        servers. In theory, whenever computers share resources with client
        machines they are considered servers. However, servers are often
        referred to as dedicated because they carry out hardly any other tasks
        apart from their server tasks.
      </p>
      <h2 id="s2">Tabulka</h2>
      <table style="margin-bottom: 3%;">
        <thead>
            <tr style="height: 50px;">
                <th rowspan="2" style="width: 200px;">Nečíslovaný seznam</th>
                <th colspan="2">Prvky stránky</th>
                <th rowspan="2">Obrázek</th>
            <tr>
                <th style="width: 12%;">Značky</th>
                <th style="width: 15%">Entity</th>
            </tr>


        </thead>
        <tbody>
            <tr>
                <td rowspan="2">
                    <ul>
                        <li>IP Adresa</li>
                        <li>Jmenná adresa</li>
                        <li>URL</li>
                    </ul>
                </td>
                <td>H2O</td>
                <td>&</td>
              <td rowspan="2"><img  src="../download.jpg" alt="Hello">
                </td>
            <tr>
                <td>c = a2 + b2</td>
                <td>&copy;</td>
            </tr>

        </tbody>
        <tfoot>
            <tr>
                <td>Odkaz:</td>
                <td colspan="3"><a href="https://www.youtube.com/">www.youtube.com</a></td>
            </tr>
        </tfoot>
    </table>
    </main>
    <footer>
      <hr>
      <h1>&copy; Patrik Tomaštík, IT1,SŠPU Opava</h1>
  </footer>
  </body>
</html>
