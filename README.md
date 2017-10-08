<h3 align="center">
    <a href="https://github.com/umpirsky">
        <img src="https://farm2.staticflickr.com/1709/25098526884_ae4d50465f_o_d.png" />
    </a>
</h3>
<p align="center">
  <a href="https://github.com/umpirsky/Symfony-Upgrade-Fixer">symfony upgrade fixer</a> &bull;
  <a href="https://github.com/umpirsky/Twig-Gettext-Extractor">twig gettext extractor</a> &bull;
  <a href="https://github.com/umpirsky/wisdom">wisdom</a> &bull;
  <b>centipede</b> &bull;
  <a href="https://github.com/umpirsky/PermissionsHandler">permissions handler</a> &bull;
  <a href="https://github.com/umpirsky/Extraload">extraload</a> &bull;
  <a href="https://github.com/umpirsky/Gravatar">gravatar</a> &bull;
  <a href="https://github.com/umpirsky/locurro">locurro</a> &bull;
  <a href="https://github.com/umpirsky/country-list">country list</a> &bull;
  <a href="https://github.com/umpirsky/Transliterator">transliterator</a>
</p>

# Centipede

The simplest automated testing tool on Earth.

## Idea

What is the simplest test you can think of for your web application? Maybe just check if all pages work? That's exactly what this tool is about.

## Usage

```
./bin/centipede run https://github.com
```

## Screenshot

![Centipede](https://raw.githubusercontent.com/umpirsky/centipede/master/resources/images/screenshot.png)

## Create a phar

First, make sure you have https://github.com/box-project/box2 installed in your system.

Then, install all dependencies:

```shell
cd <path-to-this-project>
composer install
```

Finally, build the phar:

```shell
box build
```

`centipede.phar` will be available inside `bin/` directory.

### Install globally

```shell
mv bin/centipede.phar /usr/local/bin/centipede
```

This way, `centipede` will be available on your terminal.
