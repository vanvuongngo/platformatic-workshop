# Workshop: Build React frontend with vite
React app and exposed with the gateway app.

## Create a new Watt project

- create a vite project if not already created, see https://vite.dev/guide/:
```sh
pnpm create vite my-vite-app --template react-swc-ts
```

create a directory and the change directory
```sh
mkdir my-watt && cd $_
```

```sh
pnpx wattpm create
```
- type `.` for the location where you would like to create your project
- choose `pnpm` as the package manager
- choose `@platformatic/vite` as kind of application
- input a name for your application
- location of existing project `../my-vite-app`
- choose another `gateway` application
- expose the `gateway` application

- move all dependencies in the package.json of the applications into the root [package.json](file://package.json/)

- allow build scripts
```sh
pnpm approve-builds
```

- install packages:
```sh
pnpm i
```
- start the example with watch/ hot-reload
```sh
pnpm dev
```

- or start the production version

```sh
pnpm build
```

```sh
pnpm start
```
