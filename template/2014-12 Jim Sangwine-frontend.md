# Title

### Technical Report description
Cupcake ipsum dolor. Sit amet jelly tart cake dragée jelly be ans sweet roll chocolate cake. Sweet roll halvah I love. Unerdwear.com topping tart I love marzipan. Brownie sugar plum I love sesame snaps oat cake. Apple pie lemon drops chocolate danish topping desse rt marshmallow dessert. Tart candy canes unerdwear.com ice cream tiramisu dragée applicake. Apple pie brownie sesame snaps oat cake caramels halvah danish pudding jelly beans. Gummies chocolatee cake I love croissant cookie.

- list item 1
- list item 2
- list item 3
- list item 4
- list item 5

_I love I love muffin candy canes marshmallow muffin powder. Jelly chupa chups oat cake cotton candy dessert bonbon chocolate biscuit. Powder I love bear claw. Caramels chupa chups pastry powder. Cookie macaroon muffin lemon drops carrot cake sweet roll tiramisu. Donut gummi bears gingerbread donut powder marzipan. Sesame snaps apple pie chocolate cake I love chocolate bar. Tootsie roll croissant halvah I love cheesecake dragée danish applicake. Jelly-o tart fruitcake._

**Dragée wafer pudding chocolate tiramisu cupcake gummies. Carrot cake tiramisu marzipan cotton candy. Danish tiramisu chocolate bar chocolate bar jelly beans bear claw chocolate. Jelly beans lollipop tiramisu pudding donut croissant. Bonbon chocolate cake I love. Sweet roll pudding I love gingerbread caramels dragée.**

>I love I love muffin candy canes marshmallow muffin powder. Jelly chupa chups oat cake cotton candy dessert bonbon chocolate biscuit. Powder I love bear claw. Caramels chupa chups pastry powder. Cookie macaroon muffin lemon drops carrot cake sweet roll tiramisu. Donut gummi bears gingerbread donut powder marzipan. Sesame snaps apple pie chocolate cake I love chocolate bar. Tootsie roll croissant halvah I love cheesecake dragée danish applicake. Jelly-o tart fruitcake.

[This is an link](http://assemble.io)

1. list item
2. list item
3. list item
4. list item
5. list item

**Image**
![Minion](http://octodex.github.com/images/minion.png)


## Write your code or tutorial

**CSS**
```css
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  body:first-of-type pre::after {
    content: 'highlight: ' attr(class);
  }
  body {
    background: linear-gradient(45deg, blue, red);
  }
}

@import url('print.css');
@page:right {
 margin: 1cm 2cm 1.3cm 4cm;
}

@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}

div.text,
#content,
li[lang=ru] {
  font: Tahoma, Chunkfive, sans-serif;
  background: url('hatch.png') /* wtf? */;  color: #F0F0F0 !important;
  width: 100%;
}
```

**HTML**
```html
    <code>
        <article>
            <section></section>
        </article>
    </code>
```

**Javascript**
```javascript
(function(){
    var init, ed, qt, first_init, DOM, el, i, mce = 0;
};
```

**Other**
```bash
class ntp {
    case $operatingsystem {
        centos, sles, redhat: {
        $service_name = 'ntpd'
        $conf_template = 'ntp.conf.erb'
        $default_servers = [ "192.168.100.10","192.168.100.20", ]                                   }
                    }
    if $servers == undef {
        $servers_real = $default_servers
                }
        else {
            $servers_real = $servers
            }

    package { 'ntp':
            ensure => installed,
            }

    service { 'ntp':
            name => $service_name,
            ensure => running,
            enable => true,
            subscribe => File['ntp.conf'],
        }

    file { 'ntp.conf':
            path => '&frasl;etc&frasl;ntp.conf',
            ensure => file,
            require => Package['ntp'],
            content => template("ntp/${conf_template}"),
        }
}
```

----------------------------------------------------------------------
### Add some notes for the editor

Cupcake ipsum dolor sit amet. Danish muffin tart bear claw chupa chups I love. Gingerbread gummies chocolate bar I love halvah dessert.

Toffee sweet roll pastry jelly-o. Dragée danish fruitcake applicake icing wafer chocolate bar. Bear claw candy tootsie roll tart cheesecake cake marshmallow gingerbread. Liquorice jelly-o cheesecake cake wafer halvah.

I love cookie wafer gingerbread sweet roll tootsie roll jujubes lollipop. I love carrot cake dragée wafer cotton candy lemon drops cotton candy. Pudding chocolate bar candy chocolate tart soufflé cake I love. Sugar plum pastry tootsie roll bonbon.

Halvah cotton candy danish jelly-o sweet roll muffin carrot cake. Jelly gummies soufflé dragée chocolate bar tart sesame snaps. Bear claw icing topping ice cream bear claw I love. Cake pudding sweet roll sesame snaps chocolate cake croissant bonbon topping.

I love donut chupa chups. Marzipan cookie apple pie chocolate cookie. Muffin cookie halvah chocolate bar. Croissant toffee dragée unerdwear.com tiramisu dragée.
