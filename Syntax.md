# Syntax

## Inhaltsverzeichnis
  * [Legende](#legende)
  * [Allgemeiner Syntax](#allgemeinersyntax)
  * [Sonderzeichen](#sonderzeichen)
  * [Mathematik](#mathematik)

### Legende
+ mit Zahl zu ersetzen: ``<?>``
+ Deffinition von Bereichen: ``{<?>}``

## Allgemeiner Syntax
+ neue Zeile: ``newline``
+ Trennstrich: ``mline``
+ Bruch: ``<?> over <?>``
+ Hochzahlen (Exponent):
  + einfach: ``^<?>``
  + Bereich: ``^{<?>}``
+ Tiefzahl (Subskript):
  + einfach: ``_<?>``
  + Bereich: ``_{<?>}``
+ Kommandostrich (Notlöstung): ``->``
+ Wurzel:
  + Standard: ``sqrt{<?>}``
  + N-te Wurzel: ❓

## Sonderzeichen

#### Sonstige Sonderzeichen:

#### Griechisches Alphabet:

## Mathematik
+ Matrix:
```
left ( matrix { <?>#<?>#<?>##<?>#<?>#<?> } right)

#: Trennteichen
##: Zeilen Trennzeichen
```
+ Integral:
```
int from{<?>} to{<?>} <?> dx
[<?>]^<?>_<?>
```
+ Funktion 3-grades:
```
f( x )=ax^3+bx^2+cx+d
```
+ Funktion 4-grades:
```
f( x )=ax^4+bx^3+cx^2+dx+e
```
+ Sinusfunktion:
```
f( x )a*sin( b(x+c) )+d
```
+ Kosinusfunktion:
```
f( x )a*cos( b(x+c) )+d
```
+ PQ Formel:
```
x^2+px+q=0
x_{ 1/2 }=-p over 2 +- sqrt{( p over 2)^2-q}
```
