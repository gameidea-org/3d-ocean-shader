# 3D Ocean Shader
This is the repository for complete code my [3d ocean shader](https://gameidea.org/2023/12/01/3d-ocean-shader-using-gerstner-waves/). I continously improve & update my work so changes are always expected. The details of how to implement can be found on my website. Here, only code is avaialble in case you need it.

Feel free to use it & no credit is required! However, I'll appreciate it very much if you link to my website.

## Breakdown

I am planning to write a separate breakdown post after I complete all shaders associated with ocean. However, for now, this is general overview:
1. You make a vertex shader to animate waves. I used [gerstner waves here](https://gameidea.org/2023/12/01/3d-ocean-shader-using-gerstner-waves/) for wave motion.
2. Then you apply [refraction shader](https://gameidea.org/2023/12/03/3d-refraction-shader/) to refract objects below water.
3. Then you also apply depth fog to fade objects which are deeper (post is coming soon).
4. Then you apply ocean foam to make interaction between ocean & objects more realistic (coming soon).
5. You also add more effects depending on your game (such as a tail behind ship effect) & more.
