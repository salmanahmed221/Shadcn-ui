First of all download Nextjs Follow these steps
npx-create-next-app@latest

√ Would you like to use TypeScript? ... / Yes
√ Would you like to use ESLint? ... / Yes
√ Would you like to use Tailwind CSS? ... / Yes
√ Would you like to use `src/` directory? ... / Yes
√ Would you like to use App Router? (recommended) ... / Yes
√ Would you like to customize the default import alias? ... No

After that install Shadcn
npx shadcn-ui@latest init`

Which style would you like to use? » Default
√ Which color would you like to use as base color? » Slate
√ Where is your global CSS file? ... src/app/globals.css
√ Do you want to use CSS variables for colors? .../ yes
√ Where is your tailwind.config.js located? ... tailwind.config.js
√ Configure the import alias for components: ... @/components
√ Configure the import alias for utils: ... @/lib/utils
√ Are you using React Server Components? .../ yes
√ Write configuration to components.json. Proceed? .../yes


After that your component.json file look like

{
"$schema": "https://ui.shadcn.com/schema.json",
"style": "default",
"rsc": true,
"tsx": true,
"tailwind": {
"config": "tailwind.config.js",
"css": "src/app/global.css",
"baseColor": "slate",
"cssVariables": true
},
"aliases": {
"components": "@/components",
"utils": "@/lib/utils"
}
}
