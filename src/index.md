---
# This is a full listing of available Frontmatter options, available for any content (.md) file.
title: Miller Library Makerspace
layout: page
excerpt: # used for page excerpts and META (will be overwritten if SEO used below)
author: amanda-whitmire # only displayed on Post lists and detail views. Defaults to _data/meta.authorURL
eleventyNavigation: # Required if want to display in Main Nav Bar
  key: main # "main" is required
  title: Welcome # as it will appear in the nav
  order: 1 # order to display in the nav (index = 1)
seo: # SEO values are used for OG and will overwrite 'title' and 'excerpt' above
  title:
  description:
  image: # used for OG:image and Twitter:image. Overrides default set in _data/meta.siteImage
hero: graphic # options: carousel, graphic, video, split (text & image)
heroSettings:
  height:
    mobile: # options = h-1/1 (default = full screen), h-1/2, h-1/3, h-3/4, h-9/10, h-48 (12rem, 192px), h-56 (14rem, 224px), h-64 (16rem, 256px)
    desktop: # leave blank to inherit "mobile" height (default = full screen)
  bg:
    color: # default bg-black
    image: miller_makerspace.jpg # relative to /assets/images/
    imagePosition: # options = bg-center (default), bg-left, bg-right
    opacityMobile: opacity-50 # options opacity-n, 5, 10, 15, 20, 25, 50, 75, 100 (default)
    opacityDesktop: opacity-50 # Leave blank to inherit opacityMobile, use same options as opacityMobile
  headingText: Miller Makerspace
  headingTextColor: # default = text-white (can use any TailwindCSS text-[color]-[xxx])
  headingTextCase: # default = as typed - options: uppercase, lowercase, capitalize
  subheadingText: Miller Library @ Hopkins Marine Station
  subheadingTextColor: # Leave empty to inherit headingTextColor or default (text-white) or use any text-[color]-[xxx]
  buttonText: Hours & events # no button generated if left blank
  buttonURL: /hours/ # full url required. Example: https://thisdomain.com/somepage/
  buttonTextColor: # leave blank to inherit from /src/_data/colors.buttonCustom or buttonDefault
  buttonBgColor: # leave blank to inherit from /src/_data/colors.buttonCustom.bg or buttonDefault.bg
  buttonBgHover: # leave blank to inherit from /src/_data/colors.buttonCustom.bgHover or buttonDefault.bgHover
  buttonBorder: # leave blank to inherit from /src/_data/colors.buttonCustom.border or buttonDefault.border
---


The Miller Library Makerspace at Hopkins Marine Station provides a drop-in space for Stanford students, faculty, and staff to prototype, 3D print, explore microelectronics, sew, knit, crochet, and do other hands-on making. We are [open](hours) on weekdays 9 am - 5 pm. If you'd like to use the Makerspace, please [contact us](contact) or stop by!

## Equipment & supplies
The Miller Makerspace currently has:

- Ultimaker 3 Extended 3D printer (filament)
- Form 2 3D printer (resin), Form Wash + Form Cure
- UCTRONICS Advanced Starter Kit for Arduino UNO and MEGA 2560 (x5)
- SunFounder Project Super Starter Kit V3.0 (x5)
- Kuman for Arduino Project Complete Starter Kit
- Adeept New Ultimate Starter Learning Kit for Raspberry Pi 3
- CanaKit Raspberry Pi 3 Complete Starter Kit
- Various Arduino, Raspberry Pi and Teensy boards
- Various components (resistors, capacitors, wires, etc.)
- soldering iron
- Janome HD-3000 sewing machine
- Iron & ironing board
- Cutting board & rotary cutter
- Button maker
- Crochet hooks (that you can take with you!)
- Assortment of donated fabric, thread & yarn
- Various books and patterns
- LEGO bricks
- Various modeling & craft supplies


## Background
Miller Library Head Librarian Amanda Whitmire launched the Miller Makerspace in February 2017, converting the space from a former Reference Area. You can read more about the philosophy behind the makerspace at:
- Whitmire, Amanda L. (2017). Tinkering is fundamental: why open source electronics are a natural fit in [marine] science libraries. Oral Presentation. [Stanford Digital Repository](https://purl.stanford.edu/cz459xn4262). https://purl.stanford.edu/cz459xn4262
- Whitmire, Amanda L. (2022). Implementing a 3D printing service at a marine biology library. [Stanford Digital Repository](https://purl.stanford.edu/xf227mk1917). https://doi.org/10.25740/xf227mk1917.