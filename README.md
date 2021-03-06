# Introduction

The need for Design Systems goes hand in hand with the need for scale, efficiency, and consistency in Design.

### This definition highlights the three main principles of Design Systems:

#### Efficiency

Instead of repeatedly building similar components from scratch, Design Systems enable designers & developers to reuse components and thereby increase efficiency.

#### Consistency

Design Systems introduce a shared set of principles and rules to build components. It becomes much easier to create consistent experiences across different platforms.

#### Scale

Increased efficiency and consistency lead a company to build faster products at scale.

# CSS typography

#### Figma typography link

[Figma Link](https://www.figma.com/file/qOg7ySB9ddaZLF6Xga1aF6/Master?node-id=937%3A13527)

## We have 3 main typography styles for each brand

### Barlow - Mavennet

```css
@import url('https://fonts.googleapis.com/css2?family=Barlow:wght@100;300;400;600;700&display=swap');

* {
  font-style: normal;
  line-height: 1.5;
  font-family: 'Barlow', sans-serif;
}
```

### IBM - Neoflow

```css
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@100;300;400;600;700&display=swap');

* {
  font-style: normal;
  line-height: 1.5;
  font-family: 'IBM Plex Sans', sans-serif;
}
```

### Montserrat - Metaltrail

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;600;700&display=swap');

* {
  font-style: normal;
  line-height: 1.5;
  font-family: 'Montserrat', sans-serif;
}
```

## Type hierarchy size

#### 10px - Caption 2

#### 12px - Caption 1

#### 14px - Body 2

#### 16px - Body 1

#### 18px - Heading 6

#### 20px - Heading 5

#### 24px - Heading 4

#### 34px - Heading 3

#### 48px - Heading 2

#### 60px - Heading 1

#### 96px - Main Title

## Typography Font weights

1. thin
2. light
3. regular
4. semi-bold
5. bold

## Typography CSS classes

1. Name of the font family
2. Font size
3. Font weight

### For example

```css
.ibm-96-thin {
  font-size: 96px;
  font-weight: 100;
}

.barlow-48-regular {
  font-size: 48px;
  font-weight: 400;
}

.montserrat-18-light {
  font-size: 18px;
  font-weight: 300;
}
```

# CSS color palette variables

#### Figma color palette link

[Figma Link](https://www.figma.com/file/qOg7ySB9ddaZLF6Xga1aF6/Master?node-id=825%3A11087)

## Color palette naming convention

1. Name of the color
2. Lightness percentage
3. Brand name

### For example

```css
--bodyMavennet50: rgba(127, 115, 140, 1);
--primaryNeoflow60: rgba(76, 134, 235, 1);
--fadeMetal80: rgba(187, 184, 224, 1);
```

# Figma Design system links

#### Master

[Figma Link](https://www.figma.com/file/qOg7ySB9ddaZLF6Xga1aF6/Master?node-id=30%3A2)

#### Neoflow

[Figma Link](https://www.figma.com/file/u8cnTpANdMWU1j3KM6kDKM/Neoflow?node-id=0%3A1)

#### Metatrail

[Figma Link](https://www.figma.com/file/3uB2ay348vSZoBzIWRFX7E/Metal-Trail?node-id=0%3A1)
