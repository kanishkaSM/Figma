# Ex09 Event Registration Web Application
## Date:19.12.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
import React from "react";
import screenshot202512191902421 from "./screenshot-2025-12-19-190242-1.png";

export const Image = (): JSX.Element => {
  return (
    <div className="w-[491px] h-[782px]">
      <img
        className="fixed top-0 left-[61px] w-[430px] h-[687px] aspect-[0.63]"
        alt="Screenshot"
        src={screenshot202512191902421}
      />
    </div>
  );
};

import React from "react";
import screenshot202512191902421 from "./screenshot-2025-12-19-190242-1.png";

export const Image = (): JSX.Element => {
  return (
    <div className="w-[491px] h-[782px]">
      <img
        className="fixed top-0 left-[61px] w-[430px] h-[687px] aspect-[0.63]"
        alt="Screenshot"
        src={screenshot202512191902421}
      />
    </div>
  );
};

import React from "react";
import screenshot202512191859031 from "./screenshot-2025-12-19-185903-1.png";
import textOnAPath from "./text-on-a-path.svg";

export const IphonePlus = (): JSX.Element => {
  return (
    <div className="bg-white overflow-hidden w-full min-w-[440px] min-h-[686px] relative">
      <img
        className="absolute top-0 left-0 w-[440px] h-[686px] aspect-[0.69] object-cover"
        alt="Screenshot"
        src={screenshot202512191859031}
      />

      <img
        className="absolute top-[-133px] left-[-837px] w-[251px] h-[55px]"
        alt="Text on a path"
        src={textOnAPath}
      />

      <button
        className="absolute top-[30px] left-24 w-[245px] h-[50px] bg-[#d9d9d9] cursor-pointer hover:bg-[#c9c9c9] transition-colors duration-200"
        aria-label="Book now"
      >
        <span className="absolute top-[11px] left-[10px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-[32px] tracking-[0] leading-[normal]">
          BOOK NOW
        </span>
      </button>
    </div>
  );
};
```


## OUTPUT:
![alt text](<Screenshot 2025-12-19 195017.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
