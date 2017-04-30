# collada-parser
Node module wrapper for https://github.com/jagenjo/collada.js


## installation 
`npm install collada-parser`


## build & example
`npm install & npm run dev`


## usage
```
	ColladaParser.load('./assets/boat.dae', (meshes)=> {
		//	...return all meshs
		//	mesh contains 
		//	a) buffers data ( vertices, normals, coords ... )
		//	b) model matrix 
		//	c) material
	});
```