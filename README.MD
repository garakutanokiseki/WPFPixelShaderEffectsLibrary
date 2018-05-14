# wpffx
Windows Presentation Foundation Pixel Shader Effects Library  

Library with Pixel Shader Effects and Transition Effects for WPF 3.5 SP1 ...  
  
fork from http://wpffx.codeplex.com  
  
## Project Description
Library with sample HLSL effects for WPF and Silverlight applications.  
  
Initial seed includes:  
Effects:  
BandedSwirl, Bloom, BrightExtract, ColorKeyAlpha, ColorTone, ContrastAdjust, DirectionalBlur, Embossed, Gloom, GrowablePoissonDiskEffect, InvertColor, LightStreak, Magnify, Monochrome, Pinch, Pixelate, Ripple, Sharpen, SmoothMagnify, Swirl, Tone, Toon, and ZoomBlur  

Transition Effects:  
BandedSwirl, Blings, Blood, CircleReveal, CircleStretch, CircularBlur, CloudReveral, Cloudy, Crumble, Dissolve, DropFade, Fade, LeastBright, LineReveal, MostBright, PixelateIn, PixelateOut, Pixelate, RadialBlur, RadialWiggle, RandomCircleReveal, Ripple, Rotate, Saturate, Shrink, SlideIn, SmoothSwirl, Swirl, Water, Wave.  
  
Video demonstrating the effects http://channel9.msdn.com/shows/Continuum/WPFFXDemo/  
Tutorial on writing pixel shader effects http://cid-123ec1ed6c72a14a.skydrive.live.com/browse.aspx/Public/HLSL  
Blog post announcing the library with useful links http://blogs.msdn.com/jaimer/archive/2008/10/03/announcement-wpf-shader-effects-library-on-codeplex.aspx  

Requirements:  
This requires .NET framework 3.5 SP1 and requires Direct X SDK at compile time.. (to build the PS files).  
This also uses the Shader Effects BuildTask and Templates from the WPF futures samples at http://www.codeplex.com/wpf  
For silverlight, Silverlight 3 Preview ( released at MIX09) and the corresponding tools are needed.  

## License

Microsoft Public License (MS-PL)

This license governs use of the accompanying software. If you use the software, you  
accept this license. If you do not accept the license, do not use the software.  
  
1. Definitions  
The terms "reproduce," "reproduction," "derivative works," and "distribution" have the  
same meaning here as under U.S. copyright law.  
A "contribution" is the original software, or any additions or changes to the software.  
A "contributor" is any person that distributes its contribution under this license.  
"Licensed patents" are a contributor's patent claims that read directly on its contribution.  
  
2. Grant of Rights  
(A) Copyright Grant- Subject to the terms of this license, including the license conditions and limitations in section 3, each contributor grants you a non-exclusive, worldwide, royalty-free copyright license to reproduce its contribution, prepare derivative works of its contribution, and distribute its contribution or any derivative works that you create.  
(B) Patent Grant- Subject to the terms of this license, including the license conditions and limitations in section 3, each contributor grants you a non-exclusive, worldwide, royalty-free license under its licensed patents to make, have made, use, sell, offer for sale, import, and/or otherwise dispose of its contribution in the software or derivative works of the contribution in the software.  

3. Conditions and Limitations  
(A) No Trademark License- This license does not grant you rights to use any contributors' name, logo, or trademarks.  
(B) If you bring a patent claim against any contributor over patents that you claim are infringed by the software, your patent license from such contributor to the software ends automatically.  
(C) If you distribute any portion of the software, you must retain all copyright, patent, trademark, and attribution notices that are present in the software.  
(D) If you distribute any portion of the software in source code form, you may do so only under this license by including a complete copy of this license with your distribution. If you distribute any portion of the software in compiled or object code form, you may only do so under a license that complies with this license.  
(E) The software is licensed "as-is." You bear the risk of using it. The contributors give no express warranties, guarantees or conditions. You may have additional consumer rights under your local laws which this license cannot change. To the extent permitted under your local laws, the contributors exclude the implied warranties of merchantability, fitness for a particular purpose and non-infringement.  

