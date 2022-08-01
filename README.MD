```ts
import { Developer } from "mexico";
import { 
    Javascript,
    Typescript,
    NodeJS,
    Python,
    Roblox,
    Java
} from "./technologies";

class ramondeleonca extends Developer {
    readonly isBuilding: string | Array<string>;

    constructor(isBuilding: string | Array<string>) {
    
        super({
            technologiesIKnow: [ Javascript, Typescript, NodeJS, Python, Roblox ],
            technologiesIWantToLearn: [ Java ],
            whereImStudying: "Instituto Tecnológico y de Estudios Superiores de Monterrey"
        });
    
        this.isBuilding = isBuilding;
        
    };
};

new ramondeleonca("Korus");
```

<p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=ramondeleonca&show_icons=true&theme=react" width="360px">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramondeleonca&layout=compact&theme=react" width="360px">
</src>
