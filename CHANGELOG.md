# Node.js for Mobile Apps React Native plugin ChangeLog

<table>
<tr>
<th>Current</th>
</tr>
<tr>
<td>
<a href="#0.1.4">0.1.4</a><br/>
<a href="#0.1.3">0.1.3</a><br/>
<a href="#0.1.2">0.1.2</a><br/>
<a href="#0.1.1">0.1.1</a><br/>
</td>
</tr>
</table>

<a id="0.1.4"></a>
## 2018-03-05, Version 0.1.4 (Current)

### Notable Changes

* Include the nodejs-project in the runtime NODE_PATH.
* Update `nodejs-mobile` binaries to `v0.1.4`.
* Include experimental native modules build code.
* Increase the iOS node thread stack size to 1MB.

### Commits

* [[`7780f20`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/7780f2017817723de53123a268578c89b96235e1)] - plugin: remove native modules detection (Jaime Bernardo)
* [[`99f3400`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/99f3400895d0b8626dbea37f8382f13e6aeb7ebb)] - docs: rephrasing of some README.md sections (Jaime Bernardo)
* [[`940fcfe`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/940fcfe5f14baf9976d8714b3aa321fc094821b7)] - ios: increase node's thread stack size to 1MB (Jaime Bernardo)
* [[`409b5d4`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/409b5d4e35ae0ad8fe102c26b778e6aa77888f1c)] - docs: Add native modules instructions (Jaime Bernardo)
* [[`62af6f1`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/62af6f1ed876756135ca24ec47075dee5665d7c6)] - ios: use file to override native modules build (Jaime Bernardo)
* [[`fabbd6b`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/fabbd6b6a3757af1e624c52503c7f5e8e07a6e9e)] - android: use file to override native modules build (Jaime Bernardo)
* [[`41f7dce`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/41f7dcedbf0ecaa25ea256cd069c1c6b6c94d626)] - android: use script to call npm and node on macOS (Jaime Bernardo)
* [[`3cc78d6`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/3cc78d66a313fb8ec80ba568990f907f182c2d47)] - android: use gradle tasks inputs and outputs (Jaime Bernardo)
* [[`8a7688f`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/8a7688f9b8942f0977483d7929ead7a19fbf473f)] - plugin: Build native modules automatically (Jaime Bernardo)
* [[`7ae4dd5`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/7ae4dd569b5bcc9e560ba75bbff2bdf29904a8d8)] - plugin: use nodejs-mobile-gyp for native modules (Jaime Bernardo)
* [[`d933954`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/d9339545465c67b846cbe5b9b09e5180e4846cb6)] - plugin: patch node-pre-gyp module path variables (Jaime Bernardo)
* [[`62c2670`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/62c2670b743bc60da817e8a686622fad597f1737)] - ios: native modules support (Jaime Bernardo)
* [[`af82e39`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/af82e3974d4b206b84ed20a24646a4901ae81f32)] - android: native modules support (Jaime Bernardo)
* [[`448c9ae`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/448c9ae32e70e1d2ec5239fa9d95ce22179f6eca)] - core: update nodejs-mobile v0.1.4 (Jaime Bernardo)
* [[`d478d02`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/d478d029d76e7d1de8b52d1cd5c51f7d61067b31)] - plugin: set NODE_PATH to include the project root (Enrico Giordani)

<a id="0.1.3"></a>
## 2018-01-16, Version 0.1.3

### Notable Changes

* Breaking change:
  - The `start` function from the plugin now takes the node entrypoint filename as a mandatory argument. This means current `react-native` project will have to update every `start()` call to `start('main.js')` to maintain behaviour.
* Updates `react-native` dependency version to `0.52`.
* Optimizes assets copy.
* Adds option argument to disable redirecting `stdout` and `stderr` to logcat.

### Commits

* [[`6de9bb6`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/6de9bb674e1d513547fcba2a62f0a91b556ea1d5)] - plugin: node.js entrypoint filename as argument (Jaime Bernardo)
* [[`b7f145d`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/b7f145d9945df4794f02ef1a98529b623df93958)] - plugin: Add options argument to start methods (Jaime Bernardo)
* [[`ae837b2`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/ae837b29c928bdd964db79abff06ddf925af097a)] - android: optimize assets copy (Enrico Giordani)
* [[`c32ace3`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/c32ace3e432f9ee29f5c05964f12c966611a5ddf)] - rn: add requiresMainQueueSetup and update to 0.52 (Rayron Victor)

<a id="0.1.2"></a>
## 2017-10-31, Version 0.1.2

### Notable Changes

* Update `nodejs-mobile` binaries to `v0.1.3`.
* Adds iOS simulator support.
* Updates node version and headers to `v8.6.0`.
* Shows stdout and stderr in Android logcat.

### Commits

* [[`3c5b16e`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/3c5b16e9a8a2b3eba3f513ad310adc433e0732d3)] - docs: Add mention to simulator support in README (Jaime Bernardo)
* [[`7069d4b`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/7069d4bd84d66c264eda7ea99599ef3957b36de9)] - core: update nodejs-mobile v0.1.3 (Jaime Bernardo)
* [[`70c9ac3`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/70c9ac3798ca1fa06447ffb5430a1ba7259bccbc)] - bridge: emit message event inside a setImmediate (Jaime Bernardo)
* [[`e5fbfd0`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/e5fbfd0748757a9c77dc57e4b6c11a68d13aaeac)] - android: Redirect stdout and stderr to logcat (Jaime Bernardo)
* [[`ece0079`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/ece0079d9cd798e045936048c4f65788554090de)] - meta: Update package.json fields (Jaime Bernardo)
* [[`1a5cf5e`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/1a5cf5e3c8d11a92eb88726dbb301a15dc30efa4)] - meta: Add Reporting Issues section to README.md (Jaime Bernardo)
* [[`da767ba`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/da767babc69b59e4efd9ef244766dbbf75999cc5)] - Create LICENSE (Alexis Campailla)

<a id="0.1.1"></a>
## 2017-10-02, Version 0.1.1

### Notable Changes

* Initial release.

### Commits

* [[`d1601e4`](https://github.com/janeasystems/nodejs-mobile-react-native/commit/d1601e494cf14ae4704ee7e781b0b89a645f5c50)] - Initial commit for the React Native Module (Jaime Bernardo)
