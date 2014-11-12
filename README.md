简介：这是一本牛书aosabook的续集500 Lines or Less的源码。里面每一章的代码不超过500行，实现了web服务器、爬虫、OCR等等“大型系统”，每一章由不同领域的大牛完成。看看作者列表，可以说是软件领域的名人堂。

*500 Lines or Less*
===================

> "What I cannot create, I do not understand."
>
> -- Richard Feynman

This is the source for the book *500 Lines or Less*, the fourth in the
[Architecture of Open Source Applications](http://aosabook.org) series.  As
with other books in the series, all written material will be covered by the
Creative Commons - Attribution license, and all code by the MIT License: please
see the [license description](LICENSE.md) for details.  In addition, all
royalties from paid-for versions will all go to Amnesty International.

Mission
-------

Every architect studies family homes, apartments, schools, and other common
types of buildings during her training.  Equally, every programmer ought to
know how a compiler turns text into instructions, how a spreadsheet updates
cells, and how a browser decides what to put where when it renders a page.
This book's goal is to give readers that broad-ranging overview, and while
doing so, to help them understand how software designers think.

Contributions should not focus on the details of one algorithm or on the
features of a particular language.  Instead, they should discuss the decisions
and tradeoffs software architects make when crafting an application:

*   Why divide the application into these particular modules with these
    particular interfaces?
*   Why use inheritance here and composition there?
*   Why multi-thread this but not that?
*   When should the application allow for or rely on plugins, and how should
    they be configured and loaded?

Contribution Guidelines
-----------------------

Writing for a book like this should be fun, so we're trying to keep process to
minimum. Here is our basic set of procedural guidelines:

1. When you start coding, try to submit one pull request early (e.g. somewhere
   between 50-100 lines), so that we can catch any early problems that we never
   thought about.

2. After that first commit, feel free to submit pull requests as often or as
   infrequently as you like.

3. When you are done your "first draft" of your code, do let us know in the
   commit message, or by emailing us directly (emails below). We'll assign a
   reviewer or two to your work at that time.

Contributors
------------

<table>
  <tr>
    <th>Name</th>
    <th>Affiliation</th>
    <th>Project</th>
    <th>Online</th>
    <th>GitHub</th>
    <th>Email (if you choose)</th>
  </tr>
  <tr>
    <td>Mike DiBernardo</td>
    <td>freelance</td>
    <td>editorial</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/mdibernardo">@mdibernardo</a></li>
            <li><a href="http://mikedebo.ca">mikedebo.ca</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/MichaelDiBernardo">MichaelDiBernardo</a></td>
    <td>mikedebo@gmail.com</td>
  </tr>
  <tr>
    <td>Dustin Mitchell</td>
    <td>Mozilla</td>
    <td>cluster</td>
    <td>&nbsp;</td>
    <td><a href="https://github.com/djmitche">djmitche</a></td>
    <td>dustin@mozila.com</td>
  </tr>
  <tr>
    <td>Audrey Tang</td>
    <td>g0v.tw, Socialtext, Apple</td>
    <td>spreadsheet</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/audreyt">@audreyt</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/audreyt">audreyt</a></td>
    <td>audreyt@audreyt.org</td>
  </tr>
  <tr>
    <td>Greg Wilson</td>
    <td>Mozilla</td>
    <td>web-server</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/gvwilson">@gvwilson</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/gvwilson">gvwilson</a></td>
    <td>gvwilson@third-bit.com</td>
  </tr>
  <tr>
    <td>Kresten Krab Thorup</td>
    <td>Trifork</td>
    <td>torrent client</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/drkrab">@drkrab</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/krestenkrab">krestenkrab</a></td>
    <td>krab@trifork.com</td>
  </tr>
  <tr>
    <td>Taavi Burns</td>
    <td>Points.com</td>
    <td>data-store</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/jaaaarel">@jaaaarel</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/taavi">taavi</a></td>
    <td>taavi.burns@points.com</td>
  </tr>
  <tr>
    <td>Guido van Rossum</td>
    <td>Dropbox</td>
    <td>crawler</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/gvanrossum">@gvanrossum</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/gvanrossum">gvanrossum</a></td>
    <td>guido@python.org</td>
  </tr>
  <tr>
    <td>Erick Dransch</td>
    <td>Upverter</td>
    <td>Modeller</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/ErickDransch">@ErickDransch</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/EkkiD">EkkiD</a></td>
    <td>erick.dransch@upverter.com</td>
  </tr>
  <tr>
    <td>Sarah Mei</td>
    <td>Ministry of Velocity</td>
    <td>testing framework</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/sarahmei">@sarahmei</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/sarahmei">sarahmei</a></td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td>Ned Batchelder</td>
    <td>edX</td>
    <td>templating engine</td>
    <td>
        <ul>
            <li><a href="http://nedbatchelder.com">nedbatchelder.com</a></li>
            <li><a href="https://twitter.com/nedbat">@nedbat</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/nedbat">nedbat</a></td>
    <td>ned@nedbatchelder.com</td>
  </tr>
  <tr>
    <td>Leah Hanson</td>
    <td>Google</td>
    <td>static analysis</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/astrieanna">@astrieanna</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/astrieanna">astrieanna</a></td>
    <td>leah.a.hanson@gmail.com</td>
  </tr>
  <tr>
    <td>Christian Muise</td>
    <td>University of Melbourne</td>
    <td>flow-shop</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/cjmuise">@cjmuise</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/haz">haz</a></td>
    <td>christian.muise@gmail.com</td>
  </tr>
  <tr>
    <td>Carlos Scheidegger</td>
    <td>AT&amp;T Research</td>
    <td>rasterizer</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/cjmuise">@cscheid</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/cscheid">cscheid</a></td>
    <td>carlos.scheidegger@gmail.com</td>
  </tr>
  <tr>
    <td>Marina Samuel</td>
    <td>Mozilla</td>
    <td>ocr</td>
    <td>
        <ul>
            <li><a href="http://marinasamuel.com">www.marinasamuel.com</a></li>
            <li><a href="https://twitter.com/emtwos">@emtwos</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/emtwo">emtwo</a></td>
    <td>msamuel@mozilla.com</td>
  </tr>
  <tr>
    <td>Cate Huston</td>
    <td></td>
    <td>Image Filter app</td>
    <td>
        <ul>
            <li><a href="http://www.accidentallyincode.com/">www.accidentallyincode.com/</a></li>
            <li><a href="https://twitter.com/catehstn">@catehstn</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/catehstn">catehstn</a></td>
    <td>catehuston@gmail.com</td>
  </tr>
  <tr>
    <td>Yoav Rubin</td>
    <td>Microsoft</td>
    <td>In-memory functional database</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/yoavrubin">@yoavrubin</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/yoavrubin">yoavrubin</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Dessy Daskalov</td>
    <td>Nudge Rewards</td>
    <td>Pedometer</td>
    <td>
        <ul>
            <li><a href="https://twitter.com/dess_e">@dess_e</a></li>
        </ul>
    </td>
    <td><a href="https://github.com/dessy">dessy</a></td>
    <td>dessy.daskalov@gmail.com</td>
  </tr>
</table>
