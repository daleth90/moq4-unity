# Moq4 for Unity
Necessary Moq4 dlls for Unity.

Just for conveniently import and without any modification.

## How to Install?
Open \<project-path\>/Packages/manifest.json. Add the npm registry with the scope `com.deltatimer`, then add the package into the dependency list.

```
{
  "scopedRegistries": [
    {
      "name": "NPM Registry",
      "url": "https://registry.npmjs.org/",
      "scopes": [
	    "com.deltatimer"
	  ]
    },
	// Other registries
  ],
  "dependencies": {
    "com.deltatimer.moq4-unity": "1.0.0",
    // Other packages
  }
}
```
