<img src="./preview/cover.png" alt="Cover Image" width="100%" />

<h1 align="center">(unofficial) nuxt-vscode</h1>

> This extension is not affiliated with Nuxt.js.

<p align="center">
  This Extension uses <a href="https://v3.nuxtjs.org/api/commands/add/" target="_blank">nuxi</a> but makes it interactive and easy to use with a nuxt 3 project within vscode.
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=cpreston321.nuxt-vscode#review-details">
    <img src="https://vsmarketplacebadge.apphb.com/rating-star/cpreston321.nuxt-vscode.svg?style=for-the-badge&colorA=FBBD30&colorB=F2AA08"/>
  </a> 
  <a href="https://marketplace.visualstudio.com/items?itemName=cpreston321.nuxt-vscode">
    <img src="https://vsmarketplacebadge.apphb.com/downloads-short/cpreston321.nuxt-vscode.svg?style=for-the-badge&colorA=5DDB61&colorB=4BC74F&label=DOWNLOADS"/>
  </a>
</p>

## Features

- 📖 Open Source
- 🚀 Built for [Nuxt 3](https://v3.nuxtjs.org) Project
- ✨ Nuxi built into **VS Code**.
- Full Typescript Support

## Prerequisites

- [VS Code](https://code.visualstudio.com/) `^v1.71.0`

## Feature Examples

A command pallet of commands to run in addition to adding to the `explorer` context menu for the certain folders that drive the commands.

![command pallet](./preview/command-pallet.png)

![context menu](./preview/context-menu.png)

---

- [x] `Nuxt: Add Component` - Add a component to your project
- [x] `Nuxt: Add Composable` - Add a composable to your project
- [x] `Nuxt: Add Layout` - Add a custom layout to your project.
- [x] `Nuxt: Add Plugin` - Add a plugin to the project
- [x] `Nuxt: Add Middleware` - Add custom middleware to the project.
- [x] `Nuxt: Add API Endpoint` - Adds a API endpoint to your project
- [x] `Nuxt: Add Page` - Adds a page to your project
- [ ] `Nuxt: Typecheck` - WIP ⚠️
- [x] `Nuxt: Upgrade` - Upgrade to the latest version of Nuxt

## 💻 Development

- Clone this repository
- Enable [Corepack](https://github.com/nodejs/corepack) using `corepack enable`
- Install dependencies using `pnpm install`
- Run `dev` watcher with `pnpm dev`
- Run extension in debug mode by pressing `F5` or `Ctrl + Shift + D`

## ➕ Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Credits

[`nuxi`](https://v3.nuxtjs.org/api/commands/add/) is developed by [@nuxt](https://github.com/nuxt)

[`README Inspiration`](https://github.com/zernonia) by [@zernonia](https://github.com/zernonia)

## 📜 License

[MIT](./LICENSE) License © 2022 [cpreston321](https://github.com/cpreston321)

# 📧 Contact

cpreston321 - [@cpreston321](https://twitter.com/cpreston321)

Also, if you like my work, please feel free to [buy me a coffee](https://www.buymeacoffee.com/cpreston321) ☕️

<a href="https://www.buymeacoffee.com/cpreston321" target="_blank">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png" alt="Logo" >
</a>

# 🔥 Contributors

<a href="https://github.com/cpreston321/nuxt-vscode/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=cpreston321/nuxt-vscode" />
</a>

<!-- Banner Image -->
<!-- <div
	class="relative bg-gradient-to-r from-[#255461] to-[#00DC82] h-full font-open-sans bg-cover bg-center p-2"
>
	<div class="bg-white bg-opacity-90 rounded-md shadow-lg h-full p-7 flex flex-col justify-between">
        <div>
          <img :src="mainLogo" class="w-10"/>
    	  <h1 class="text-4xl font-bold line-clamp-3 pb-1">{{ title }}</h1>
          <p class="text-gray-700 italic">(un-official)</p>
        </div>
		<div class="mt-3 flex items-center justify-between">
			<div class="flex items-center space-x-2 text-lg">
				<img class="w-10 h-10 rounded-full" crossorigin="anonymous" :src="avatar" />
				<span class="font-semibold">{{ author }}</span>
			</div>
			<div>
				<img :src="logo" alt="logo" class="h-12" />
			</div>
		</div>
	</div>
</div> -->
