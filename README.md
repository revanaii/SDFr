# SDFr
a signed distance field baker for Unity

![gif](https://www.dropbox.com/s/ka6mlx2tef1lboa/oNrM0ZMpEr.gif?raw=1)

about
-----

- Generates signed distance fields as Texture3D in RHalf format for use with ray marching or the Visual Effect Graph.
- Written distances are between -1 and +1, normalized to the bounding box magnitude.
- Takes advantage of Jobs and Burst + Unity Mathematics, comment out the #define in SDFVolume.cs if Burst & Mathematics should not be used.
- Tested in Unity 2018.3

![png](https://www.dropbox.com/s/zd07uve5o4ahgls/Unity_S1LNYsiRd5.png?raw=1)

License
-------
[MIT](LICENSE.md)
