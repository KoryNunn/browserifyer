browserifer
==========

browserifer is a simple file watcher and browserif runner.

When you save changes to a .js file being watched browserifer is automagicly run for you.

Installation
------------

	npm install -g browserifer
	
	
Usage
---------

browserifer [options]

Options:

  -h, --help               Output usage information
  
  -V, --version            Output the version number
  
  -v, --verbose            Verbose output
  
  -w, --watch [path]       Watch Path [default ./]
  
  -i, --input [fileName]   Input File [default ./main.js]
  
  -o, --output [fileName]  Output File [default ./main.browser.js]
  
  -t, --throttle [milliseconds]  Minimum time between processing (milliseconds) [default 300]
  
  
  
Warranty
---------

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
