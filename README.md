#Add Readme

Refer Note : https://sbcode.net/threejs/

npm install three --save-dev  
npm install @types/three --save-dev

npm install dat.gui@latest --save-dev
npm install @types/dat.gui@latest --save-dev

npm install lil-gui
npm uninstall dat.gui
npm uninstall @types/dat.gui

https://polyhaven.com/

npm install jeasings --save-dev

npm install --global @gltf-transform/cli

gltf-transform --help

Using 
gltf-transform.cmd optimize '.\public\models\eve$@walk.glb' '.\public\models\eve$@walk_compressed.glb' --compress draco --texture-compress webp

gltf-transform.cmd optimize .\public\models\worker@walk.glb .\public\models\worker@walk_cp.glb --compress draco --texture-compress webp