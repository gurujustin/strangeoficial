<div align="center" id="top">
  <h2>
    <i>Developer Full Stack</i>
  </h2>
  <a href"https://github.com/strangeoficial?tab=followers">
        <img alt="GitHub followers" src="https://img.shields.io/github/followers/strangeoficial?colorA=1e1e28&colorB=c9cbff&logo=Github&style=for-the-badge" />
   </a>
  <a href="https://twitter.com/strange_silva">
     <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/strange_silva?colorB=c6aae8&colorA=1e1e28&label=Follow&logo=twitter&logoColor=white&style=for-the-badge">
  </a>
  <a href="https://discord.gg/5dZPVytKnn">
    <img alt="Discord server"  src="https://img.shields.io/discord/914797672907563041?colorA=1e1e28&colorB=c6aae8&label=Discord&logo=discord&logoColor=white&style=for-the-badge">
  </a>
</div>

<br />

<div style="width: 10px;"></div>
<a  href="https://discord.gg/5dZPVytKnn"><img align="right" src="https://discordapp.com/api/guilds/914797672907563041/widget.png?style=banner4"/></a>

```typescript
import { message } from "howstrange";

class StrangeWorkflow {
  private message: string[];
  
  contructor() {
    this.message = ["ts", "js", "py", "c"]
  };
  
  public async function SendMessage(): Promise<string> {
    const send = await message();
    
    const msg = send(this.message);
    
    return msg;
  };
};

export { StrangeWorkflow };
``` 

<h4 align="center">

![metrics](./github-metrics.svg)
