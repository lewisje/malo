![http://www.allapis.com/malo/malo.png](http://www.allapis.com/malo/malo.png)

**Malo** is ultra small css library for building web sites.

It is meant to be structural base for small or medium web sites.

Malo derives from it's bigger brother [Emastic CSS Framework](http://code.google.com/p/emastic/).

**Why should you use Malo?**

Because it's:
  * Ultra small (compressed is 0,25 kb or 8 lines of CSS! )
  * Personalized width of the page in (%, px, em)
  * Super flexible.
  * Easy to use.

**How Malo works?**

Malo is based on the principle that every column can be divided into two, three, four and five parts.

  * 100% = 50% + 50%
  * 100% =~ 33,33% + 33,33% + 33,33%
  * 100% = 25% + 25% + 25% + 25%
  * 100% = 20% + 20% + 20% + 20% + 20%

Also you can use nested columns

100% = 50% + 50% ( and inside 25% + 25% + 25% + 25%)

I think that with this system you can cover 85% of every grid you can imagine.

**About CSS**

malo.css is made of two parts: basic reset and the grid system

The grid part is made of classes from dp100 (div percent 100) to dp20 floated to left and using the hack for IE:
`display: inline; *margin-left:-0.04em;` (be careful if you change default 1em = 16px)

**Examples:**

  * [Test1](https://dl.dropbox.com/u/2111778/Malo/Malo-Tutorial.html)
  * [Test2](https://dl.dropbox.com/u/2111778/Malo/Malo-Tutorial1.html)
  * [Malo1](https://dl.dropbox.com/u/2111778/Malo/malo1.html)
  * [Malo2](https://dl.dropbox.com/u/2111778/Malo/malo2.html)
  * [Malo3](https://dl.dropbox.com/u/2111778/Malo/malo3.html)
  * [Malo4](https://dl.dropbox.com/u/2111778/Malo/malo4.html)
  * [Malo5](https://dl.dropbox.com/u/2111778/Malo/malo5.html)
  * [Malo6](https://dl.dropbox.com/u/2111778/Malo/malo6.html)
  * [Malo7](https://dl.dropbox.com/u/2111778/Malo/malo7.html)
  * [Malo8](https://dl.dropbox.com/u/2111778/Malo/malo8.html)
  * [Malo9](https://dl.dropbox.com/u/2111778/Malo/malo9.html)
  * [Malo10](https://dl.dropbox.com/u/2111778/Malo/malo10.html)
  * **New:** [Malo ID](https://dl.dropbox.com/u/2111778/Malo/Malo_ID.html)
  * [Prototyping with Malo CSS Library](http://www.vcarrer.com/2009/01/prototyping-with-malo-css-library.html)

**Tested with:**

IE:5.01,5.5,6,7,8, Firefox:1.5,2,3, Opera:8.53, 9.23, Safari:2.0 - 4.0 , Chrome 0.3, Konqueror: 3.5, 4.0, camino-1.6.5, kazehakase-0.5.2, galeon-2.0.4, seamonkey: 1.1.12, 2.0

_Note:In IE the columns(div) will have -0.04em. That will prevent the grid from breaking apart._

[Comments and suggestion](http://code.google.com/p/malo/wiki/Ideas)