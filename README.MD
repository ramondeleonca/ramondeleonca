```ts
import { Developer } from "mexico";
import { 
    Javascript,
    Typescript,
    NodeJS,
    Python,
    Roblox,
    WebView,
    CSS,
    SASS,
    GSAP,
    Figma,
    Ejs,
    Java,
    React,
    NextJS
} from "./technologies";

class ramondeleonca extends Developer {
    readonly isBuilding: string | Array<string>;

    constructor(...isBuilding: string | Array<string>) {
    
        super({
            technologiesIKnow: [ Javascript, Typescript, NodeJS, Python, Roblox, WebView, CSS, SASS, GSAP, Figma, Ejs, React, NextJS, Java ],
            technologiesIWantToLearn: [ ],
            whereImStudying: "Tec de Monterrey"
        });
    
        this.isBuilding = isBuilding;
        
    };
};

new ramondeleonca("Korus", "Blue Ignition's codebase");
```

<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=ramondeleonca&show_icons=true&theme=react" height="175px">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramondeleonca&layout=compact&theme=react" height="175px">
</src>
