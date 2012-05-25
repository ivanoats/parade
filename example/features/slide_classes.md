!SLIDE

# Slide Classes

!SLIDE center

## center

![octocat](../images/octocat.png)

centers images on a slide

!SLIDE

```
    !SLIDE center

    ## center

    ![octocat](../images/octocat.png) 
```

!SLIDE full-page

## full-page

![octocat](../images/octocat.png)

allows an image to take up the whole slide

!SLIDE bullets

## bullets

* One
* Two
* Three
* Four
* Five

sizes and separates bullets properly (fits up to 5, generally)

!SLIDE smbullets

## smbullets

* One
* Two
* Three
* Four
* Five

sizes and separates more bullets (smaller, closer together)

!SLIDE subsection

## subsection

# titles

creates a different background for titles

!SLIDE command

## command

monospaces h1 title slides

!SLIDE commandline

## commandline

```bash
$ command
response
```

for pasted commandline sections (needs leading '$' for commands, then
output on subsequent lines)

!SLIDE code

## code

monospaces everything on the slide

!SLIDE incremental bullets

## incremental bullets

* one
* two
* three

!SLIDE incremental commandline

## incremental commandline

```bash
$ command
response
```

!SLIDE small

## small

make all slide text 80%

!SLIDE smaller

## smaller

make all slide text 70%

!SLIDE execute

## execute

```javascript
result = 1 + 1;
```

> Supports Javascript, Coffeescript and Ruby highlighted code slides, you can
click on the code to execute it and display the results on the slide