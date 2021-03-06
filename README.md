![alt text](https://github.com/tojynick/Stylized-Water-Shader/blob/main/Readme%20Resources/Thumbnail.png)

## Features
* **Shallow and deep colors**
* **Foam**, both *simple* and *advanced*
* **Transparency and distortions**
* **Waves**
* **Caustics**
* **Mobile optimized!**

### Toggleable Features
* **Distortions** - simulates refraction by reading from opaque texture using distorted UV, **expensive**. *Requires Opaque Texture to be enabled.*
* **Caustics**
* **Waves**
* **Foam Type** - simple or advanced. Simple is cheap, advanced is expensive, but gives you much more control.

## Important Notes
### Compatability
The shader is tested only in **Unity 2021** and only with **URP**, so I cannot guarantee it will work properly in earlier versions of Unity or different render pipelines.
### URP Settings
Please make sure that **Depth Texture** and **Opaque Texture** are enabled in your URP settings. Without it the shader will work incorrectly.
### Orthographic projection
The shader's depth effects like **foam**, **water shallow, and deep colors** don't work with an *orthographic camera projection* for some reason.

## Examples
[YouTube Video](https://www.youtube.com/watch?v=S5xWj7hhmws)

![alt text](https://github.com/tojynick/Stylized-Water-Shader-Unity-URP/blob/main/Readme%20Resources/Stylized%20Water%20Example.gif)

### Screenshots

#### Blue Water
![alt text](https://github.com/tojynick/Stylized-Water-Shader/blob/main/Readme%20Resources/Blue%20Water.jpg)

#### Pink Water
![alt text](https://github.com/tojynick/Stylized-Water-Shader/blob/main/Readme%20Resources/Pink%20Water.jpg)

#### Purple Water
![alt text](https://github.com/tojynick/Stylized-Water-Shader/blob/main/Readme%20Resources/Purple%20Water.jpg)

