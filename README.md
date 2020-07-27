# Yr Iaith Rhaglennu Rust

![Statws Adeiladu](https://github.com/rust-lang/book/workflows/CI/badge.svg)

Mae'r storfa hon yn cynnwys ffynhonnell llyfr "Yr Iaith Rhaglennu Rust".

[Mae'r llyfr ar gael ar ffurf papur gan No Starch Press][nostarch].

Gallwch hefyd ddarllen y llyfr ar-lein am ddim. Gweler y llyfr a gynhwysir yn fersiynau [sefydlog][], [beta][], neu [beunosol][] Rust. Byddwch yn ymwybodol y gallai problemau yn y ferisynau hynny fod wedi'u trwsio yn y storfa hon eisoes, fel y mae'r fersiynau hynny'n cael eu diweddaru yn llai aml.

Gweler [rhyddhadau][] i lawrlwytho dim ond y cod sy'n ymddangos yn y llyfr.

## Gofynion

Mae angen ar [mdBook][] i adeiladu'r llyfr, yn ddelfrydol yr un fersiwn 0.3.x y mae rust-lang/rust yn ei ddefnyddio yn [y ffeil hon][rust-mdbook]. I'w osod:

```bash
$ cargo install mdbook --vers [version-num]
```

## Adeiladu

I adeiladu'r llyfr, teipiwch:

```bash
$ mdbook build
```

Bydd yr allbwn yn is-blygell `book`. I edrych arno, agorwch e yn eich porwr gwe.

_Firefox:_
```bash
$ firefox book/index.html                       # Linux
$ open -a "Firefox" book/index.html             # OS X
$ Start-Process "firefox.exe" .\book\index.html # Windows (PowerShell)
$ start firefox.exe .\book\index.html           # Windows (Cmd)
```

_Chrome:_
```bash
$ google-chrome book/index.html                 # Linux
$ open -a "Google Chrome" book/index.html       # OS X
$ Start-Process "chrome.exe" .\book\index.html  # Windows (PowerShell)
$ start chrome.exe .\book\index.html            # Windows (Cmd)
```

I roi profion arno:

```bash
$ mdbook test
```

## Cyfrannu

Byddem wrth ein boddau gyda'ch help! Gwelwch [CONTRIBUTING][contrib] i ddysgu am y mathau o gyfraniadau rydym yn chwilio amdanynt.

### Cyfieithiadau

Byddem wrth ein boddau gyda help i gyfieithu'r llyfr! Gwelwch label [Cyfieithiadau][] i ymuno â'n hymdrechion sydd ar y gweill. Agorwch broblem newydd i gychwyn gweithio ar iaith newydd! Rydym yn aros am [gefnogaeth mdbook amlieithog][] cyn inni gyfuno â nhw, ond mae croeso ichi gychwyn arni!

## Gwirio Sillafu

I wirio ffeiliau ffynhonnell am wallau sillafu, gallwch ddefnyddio'r sgript `spellcheck.sh`. Mae angen geiriadur o eiriau dilys arni, a ddarperir yn `dictionary.txt`. Os yw'r sgript yn cynhyrchu canlyniadau cadarnhaol anghywir (er engrhaifft, rydych wedi defnyddio'r gair `BTreeMap` y mae'r sgript yn ei ystyried ei fod yn annilys), mae angen arnoch ychwanegu'r gair hwn at `dictionary.txt` (cadwch drefn y wyddor am gysondeb).

[nostarch]: https://nostarch.com/rust

[sefydlog]: https://doc.rust-lang.org/stable/book/
[beta]: https://doc.rust-lang.org/beta/book/
[beunosol]: https://doc.rust-lang.org/nightly/book/

[rhyddhadau]: https://github.com/rust-lang/book/releases

[mdBook]: https://github.com/rust-lang-nursery/mdBook
[rust-mdbook]: https://github.com/rust-lang/rust/blob/master/src/tools/rustbook/Cargo.toml

[contrib]: https://github.com/rust-lang/book/blob/master/CONTRIBUTING.md

[Cyfieithiadau]: https://github.com/rust-lang/book/issues?q=is%3Aopen+is%3Aissue+label%3ATranslations
[gefnogaeth mdbook amlieithog]: https://github.com/rust-lang-nursery/mdBook/issues/5
