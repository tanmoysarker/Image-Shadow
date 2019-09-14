# Image-Shadow
A simple npm package for using shadow effect on images
# What is this?
Get perfect shadows every time for the non-designer
# Instalation
npm i imageshadower

Then ...

import { imageshadow } from "imageshadow";

imageshadow({
    shadow_type: "soft",
    padding: false
});
# Options
imageshadow supports 2 options, noth of which are optional:
shadow_type - hard | soft (Defaults to soft)
padding - boolean (Defaults to false)
