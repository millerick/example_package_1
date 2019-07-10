Run the following:
```
npm i
npm ls
```
Observe the following output from `npm ls`:
```
example_package_1@1.5.0 /src/example_package_1
└─┬ async@2.6.2
  └── lodash@4.17.13
```
Run the following:
```
npm ci
npm ls
```
Observe the following output from `npm ls`:
```
example_package_1@1.5.0 /src/example_package_1
└─┬ async@2.6.2
  └── lodash@4.17.13
```
Note that the output is identical to each other.
