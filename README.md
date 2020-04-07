3D Depth Map Creator
====================

Images with depthmap playground.

3D Depth Map Creator shows Google Camera Lens Blur photos with 3D parallax effect and creates animated GIFs from them. Plus extracts the depth map and enables you to create your own!

Contributions more than welcome!

## How to build

- Install node + npm
- Run anywhere: `npm install -g grunt-cli bower`
- Run in project directory: `npm install` and `bower install`
- For local development server run: `grunt serve`
- For deployment: `grunt build`

## Docker image
If you want to simply run locally, you can use [Docker.io](https://www.docker.com/).

Once docker installed, simple run:
```
$ docker run --rm -t -i -p 9000:9000 essembeh/3d-depth-map-creator
```

Then go to [localhost:9000](http://localhost:9000)

## How to help

There is a lot of stuff you can do with depthmaps. If you have ideas and you know how to code,
You already know how to help ;) I'm pretty lax on formalities, just make it work and at least 
try to follow conventions of the code...

## License

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

