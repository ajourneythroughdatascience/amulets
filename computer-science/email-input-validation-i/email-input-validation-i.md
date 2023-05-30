<article class="first">
  <div class="title">
    <h1>Validatio Velectrica: Email Input Validation I</h1>
  </div>
</article>

<p align="center">
  <img src="https://pabloagn.com/wp-content/uploads/2023/04/M001A037_validatio-velectrica-email_input_validation_i_432_REDUCED.jpg" height="750" class="amulet-image">
</p>

---

[![made-with badge](https://img.shields.io/static/v1?label=Made%20with&message=Obsidian&color=7d5bed&logo=obsidian&labelColor=1a1a1a&style=flat)](https://obsidian.md/)

[![type](https://img.shields.io/static/v1?label=Type&message=amulet&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAAi0lEQVRIS+2WMQ7AIAhF/UNXrtP7rz2OYxeqTWxMTBUSxQVXfnzyQQKC8YExL7zAGCNbgIkIsIKVhBw4vbR7unR6Gp0LvwxXd2v+EvkdDpxWXpWlRTyi9/pABRyBJHEHSlxSadxSlV0SsVsqcUml2W/pynWxnsXNisHMRxrCl8qvH3ECnQDuOmy+0zwB4WNxmUKgwwAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/amulets/) [![category](https://img.shields.io/static/v1?label=Category&message=computer-science&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAB9UlEQVRIS6VWMU7DQBDkDAQEdrAoCISCAomCL1DxC95Azy9oeQS/oOIHVFAgREFoCHGCRSzZzEU+63LZ9W6CO/vudmZ2d9Zn1pTPaDSqut2usduHw+FpFEUv7t1fk8LNAkiPDWj3+ADuTPjNvXMxWwGzLCuqqtqwh5MkiY0xEwfOAfrEKFAWUBO4DZQDXgCEqjuouvbZUanUrocpngMMVUkKtKC+WhFQUudAUd8r1PkepJ/w7Tysn4uzkNJlascF9WOASAki6w0xrn19b3Gpps5y3kRfJADPZgr9gJSP0EgDHDiQ/Mp50PfxAmDtuQhsZmb/z0OVhwSkmGrSGp5bGRDp3EFaJ5JaiahdZ2vYNj/JkWVMgW7sgNw2yOW+99gacp7TeFE72OcUrgo4Ho93+/3+D5T9QmGHm0BNSnHgMI7jj9Ai2tElZGCK9S3S+GA4BcNNydBaIuEstu/iLJWCa+pLDm+Nz+xQAsBenucnRVG8asFq0s/Yf9YoVAI21wyn3N4I7M1A8ijWHwB42XrFqIO9YfMRlVqqyXC5ukED3nIEVJcoBXv1lmWa5gIpeeQioyTWVj1uXf0DpgKUZbmfpunXKnVnU9rWDKiTHRSDNkDu36iqIQK/Q+mxU8sBYniL/1EVoJ9Wqwo/5x6Cf9YKv6Em1XbNH5bGfSwvuRe1AAAAAElFTkSuQmCC&labelColor=1a1a1a&style=flat)](https://pabloagn.com/categories/computer-science/) [![technologies](https://img.shields.io/static/v1?label=Technologies&message=RegEx&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAAACXBIWXMAAAsTAAALEwEAmpwYAAAA1klEQVR4nM2RMW7CUBBEnUikIQUIlBJxrrQgJG7ABRBnoUkaWhpoUgWJlgNYbvz/G1dUi1ayoy87rpOtVrszs6OdLPtXlef5UNJXjHHcCwohjMzsKZ3FGN+Bq/e+c0xHGfiWtEznkg6SNnW/dIxjs0YJ2AMnM3tJSFPgHkKY17gBcAQ+zOw5A3aSbsCkdW0NnNOZY2rstpcInJ3cS/SzwGdqtSzLmdusquqtIXWsehVF8QpcJK1qmxt/TMv6wjE/z0leP27i8Ag8inT/axxtAQ+9o/zn9QD3JOiyTjnQEQAAAABJRU5ErkJggg==&labelColor=1a1a1a&style=flat)](https://pabloagn.com/technologies/) [![website article](https://img.shields.io/static/v1?label=Website&message=Post%20Link&color=e60048&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAcCAYAAAByDd+UAAAACXBIWXMAAAsTAAALEwEAmpwYAAAB+ElEQVR4nO2VOYgUURCGR/BAI4MN1EwjI89EMDYQvNBNNNlcE0VBUdlUUSMjj2BF2UDRePDAwGzNF2GNPIYd8Hjv/6YnEHSf/FIDPTJiu4nJFBTd1Kv6/nrVBd1q/S8DJiU9AmaBm5LOSjoATPwDY0LSQUnnzDArmJOjkqclvQceSHohaR6oJC1JeiPprqT9pZSVg5pSyirH4sw5S1EzbwZwP5jTIwWBdj1meEppZ6/XOyXpCdCX9Am4Fv45Yo+Bk1VV7ag3FNz2kKC7yznvHiX4u3U6nXU55xPAW7vfHfvLmNtmW8NaFux67k0Ea03esTfJJQTj23bHgiNtPNK6jZem3Wpg46Wp23hp2q0GNl6axksjaRGYkXRF0mnHq6ra2HSk/X5/k6RDks6YEazFPwnuBS5KuirptqTnkj4CJZ4zwNFSytqBoP/2wDHgXi33A/BM0i2zzDR7SBC4LGlPr9fb5huVUlYMus45b5E0FYJfgQS8C8/Al7jJVEpp86DODLPMNDs0up7xXBQZVKLLb8CCpIfA+ZzzvpTS+lLKGuAI8DT8cClltc+c49yoWQjGL140ao25oW8QXW1IKe3KOR8Hbkh66ZtI+i7plaG+iR244JjP3HDkXnetGWbVp9XYopHtHgvwWtIPu9+BSx7bssBNDdhqX07xT/Jbz1SBBDGHAAAAAElFTkSuQmCC&labelColor=1a1a1a&style=flat)](https://pabloagn.com/amulets/email-input-validation-i/)

Input validation lets us ensure only properly formed data is entering the workflow in an information system, preventing malformed data from reaching the database and triggering malfunction of various downstream components. [RegEx](https://pabloagn.com/technologies/regex/) is a powerful pattern-matching engine designed to search and match complex patterns: From email addresses to IP addresses to phone numbers to infinitely complex text patterns.

In this Amulet, we'll use regular expressions to match some email addresses.

We'll be using a text file containing email addresses which can be found [here](https://raw.githubusercontent.com/ajourneythroughdatascience/amulets/master/computer-science/email-input-validation-i/email_addresses.txt).

---

# Table of Contents
- [Problem Statement](#problem-statement)
- [Requirements](#requirements)
- [Unlocking the Amulet](#unlocking-the-amulet)
	- The first group]()
	- The second group]()
	- The third group]()
	- Composing the complete expression]()
- [Conclusions](#conclusions)
- [References](#references)
- [Copyright](#copyright)

---

# Problem Statement
We are presented with a set of email addresses containing different structures. A sample of the complete set can be found below:

```
dougie.jones@luckyseven.com
rodion.raskolnikov@stpetersburgphilosophers.ru
dunya.raskolnikova@moscowfeminists.ru
semyon.marmeladov@petersburgtragedies.ru
petr.luzhin@urbanwealth.ru
arkady.svidrigailov@noblesdelight.ru
john.tavner@milwaukeemusicians.com
tom.tavner@unseenheroes.us
agnes.tavner@quietkeepers.com
```

Our job is to match all the valid email addresses, using whichever flavor suits us best. A typical email address is composed of the following parts:
- A unique username: `dougie.jones`
- A domain name: `luckyseven`
- A top-level domain name: `.com`

---

# Requirements
- Only the valid addresses must be matched.
- Each address must be a complete and single match, meaning we must not do partial matches on fragments of the address.
- Our expression has to be flexible, meaning it has to account for all possible and top-level domains.
- We must name each part of the email address with its respective section. That means:
	- Username
	- Domain name
	- Top-level domain name


<div class="think-box" align="center">
  <div class="content">
    <img src="https://pabloagn.com/wp-content/uploads/2023/04/Diamond_Icon_White.png" width="70" height="70" class="icon">
    <h2 class="main-header">Tackling Groups</h2>
    <p class="main-description">Tackling group by group and composing a final expression in the end can significantly ease the task.</p>
    <a href="https://www.merriam-webster.com/dictionary/memory">
      <button class="more-button">Learn More</button></a>
  </div>
</div>

The RegEx expression can be written in any flavor using any tool. However, the solution only includes the expression in PCRE2 flavor (*PHP >=7.3*).

---

# Unlocking the Amulet
Let us break down this problem into groups:
- The first group should include the entire username, including any dots or other valid separators we might encounter.
- The second group should include the domain name. This can vary, since there are custom domains, so we cannot just limit our RegEx to the commercial ones, such as google, yahoo, etc.
- The third group should include the top-level domain, which should also not be limited to known domains, since every day, new ones are created. For example, `.ai` did not exist a few years back.

## 1. The first group
We can start with specifying a beginning-of-line metacharacter, followed by the capturing group name, and any alphanumerical character along with some special characters:

##### **Code**
```RegEx
^(?<username>[A-Za-z0-9-_.]+)\@
```

We can then repeat this using the `+` metacharacter, which matches the previous token between one and unlimited times.

At the end of our group, we include the `@` symbol including an escape character to make sure that it's not taken as a special character.

## 2. The second group
We can continue with the domain name, which will practically include any alphanumerical character as well as dash `-` and underscore `_` characters. Other special characters are not allowed.

##### **Code**
```RegEx
(?<domain_name>[A-Za-z0-9-_]+)
```

## 3. The third group
We can end our expression by including the top-level domain name, and an end-of-line metacharacter. The top-level domain can consist of multiple groups. For example, `.gov.au` is a valid option, and we need to account for that. This can be managed using an optional metacharacter `?` at the end of the second specification.

##### **Code**
```RegEx
(?<top_level_domain_name>\.[A-Za-z0-9_]+)(\.[A-Za-z0-9_]+)?$
```

As we can see, we limit the types of special characters we can use, since top-level domains do not accept characters other than alphanumerical or underscores.

## 4. Composing the complete expression
In the end, we get something like such:

##### **Code**
```RegEx
^(?<username>[A-Za-z0-9-_.]+)\@(?<domain_name>[A-Za-z0-9-_]+)(?<top_level_domain_name>\.[A-Za-z0-9_]+)(\.[A-Za-z0-9_]+)?$
```

Which, if plotted using a RegEx railroad diagram visualizer (*[Regex-Vis](https://regex-vis.com/) was used for this example*), results in something like such:

<p align="center">
  <img src="https://pabloagn.com/wp-content/uploads/2023/05/M001A037_01.png">
</p>
###### *Figure 1: Railroad Diagram for Complete Expression*

---

# References
- [Groups and backreferences, Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions/Groups_and_backreferences)
- [GeeksForGeeks, PHP | Regular Expressions](https://www.geeksforgeeks.org/php-regular-expressions/)

---

# Copyright
Pablo Aguirre, Creative Commons Attribution 4.0 International, All Rights Reserved.