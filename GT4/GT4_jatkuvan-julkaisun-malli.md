##Harjoitustehtävä 1 - Ketterän kehityksen periaatteet käytännössä...


Tavoite:

Tututstuaan Agilo Trac-työkaluun ja tarkastellaan sen avulla miten hommat etenee sprinttien aikana

Ryhmä asentaa oman Agilon virtuaalikoneena ja importoi hakemistossa olevan "product-backlog.csv* tiedoston sisällön
ko. työkaluun

* [Mikä on Agilo?](http://www.agilofortrac.com/)
* [Mikä on Trac?](https://trac.edgewall.org/)
* [Mikä on Agile42](http://www.agile42.com/en/agile-info-center/)


Mitä tehdään:

* Tutustutaan miten agilo toimii
* Luodaan taskeja
* Luodaan ryhmässä käyttäjätarinoita, jotka viedään TRAC työkaluun
* Viedään kuvitteellista kehitystä läpi "virtuaalisten sprinttien"
* Tarkastellaan Burndown näkymän muutoksia
* 

Mitä pitää ymmärtää!

* Kannattaa kerrata käsitteet: Story Points, Product Backlog, Sprint, User Story, Product Owner, Scrum Master, Acceptance Criteria, Planning Poker
* 


###Miten ihmeessä aikaa nopeutetaan:) ?

Sprintin etenemistä vauhditetaan muokkaamalla virtuaalikoneen sisäistä kelloa. Tämän seurauksena joudumme poistamaan virtuaalikoneesta kellosynkronoinnin isännän RTC-aikaan. Muokkaus on mahdollista käyttämällä muokkattua Virtualbox [konfiguraatio tiedostoa](https://github.com/JAMK-IT/IIO12110-ohjelmistotuotannon_kaytannot/blob/master/HT1/agilo-appliance-debian-8.5.0-amd64.vbox).

Kun muutos on tehty. Voi aikaa siirtää virtuaalikoneessa konsolilta käyttäen komentoa: 

_sudo data -s "next day"_






