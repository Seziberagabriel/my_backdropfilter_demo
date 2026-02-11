# BackdropFilter Demo

**Widget:** BackdropFilter  
**Description:** Demonstrates a login form with a blurred background using Flutter's BackdropFilter widget.

## Run Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/Seziberagabriel/my_backdropfilter_demo.git

**Attribute 1: filter: ImageFilter.blur(sigmaX, sigmaY)**

Default value: sigmaX = 0, sigmaY = 0 → no blur applied

Live change/demo: Increase to sigmaX = 5, sigmaY = 5 while running the app

Visual effect: Background becomes blurred behind the widget

Why a developer would adjust: To create visual hierarchy, soften background content, or achieve a glassmorphism effect

**Attribute 2: Container.color with opacity**

Default value: Colors.white.withOpacity(1.0) → fully opaque, background not visible

Live change/demo: Set Colors.white.withOpacity(0.3)

Visual effect: Background blur is visible through the container; the box looks semi-transparent

Why a developer would adjust: To balance visibility of the blur and content, or match UI design requirements

**Attribute 3: TextStyle in Text widget**

Default value: fontSize = 14, fontWeight = normal

Live change/demo: fontSize = 24, fontWeight = bold

Visual effect: Text becomes larger and bolder, stands out against blurred background

Why a developer would adjust: To highlight key information, improve readability, or match design aesthetics