<h1 align="center">ts-jest</h1>

<p align="center">A Jest transformer with source map support that lets you use Jest to test projects written in TypeScript.</p>

<p align="center">
  <a href="https://www.npmjs.com/package/ts-jest"><img src="https://img.shields.io/npm/v/ts-jest/latest.svg?style=flat-square" alt="NPM version" /> </a>
  <a href="https://www.npmjs.com/package/ts-jest"><img src="https://img.shields.io/npm/dm/ts-jest.svg?style=flat-square" alt="NPM downloads"/> </a>
  <a href="https://snyk.io/test/github/kulshekhar/ts-jest"><img src="https://snyk.io/test/github/kulshekhar/ts-jest/badge.svg?style=flat-square" alt="Known vulnerabilities"/> </a>
  <a href="https://coveralls.io/github/kulshekhar/ts-jest?branch=main"><img src="https://coveralls.io/repos/github/kulshekhar/ts-jest/badge.svg?branch=main" alt="Coverage status"/> </a>
  <a href="https://actions-badge.atrox.dev/kulshekhar/ts-jest/goto?ref=main"><img alt="GitHub actions" src="https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fkulshekhar%2Fts-jest%2Fbadge%3Fref%3Dmain&style=flat-square" /> </a>
  <a href="https://github.com/kulshekhar/ts-jest/blob/main/LICENSE.md"><img src="https://img.shields.io/npm/l/ts-jest.svg?style=flat-square" alt="GitHub license"/> </a>
</p>

<img src="./icon.png" align="right" title="ts-jest Logo" width="128" height="128">

It supports all features of TypeScript including type-checking. [Read more about Babel7 + `preset-typescript` **vs** TypeScript (and `ts-jest`)](https://kulshekhar.github.io/ts-jest/docs/babel7-or-ts).

---

| We are not doing semantic versioning and `23.10` is a re-write, run `npm i -D ts-jest@"<23.10.0"` to go back to the previous version |
| ------------------------------------------------------------------------------------------------------------------------------------ |

[<img src="./website/static/img/documentation.png" align="left" height="24"> View the online documentation (usage & technical)](https://kulshekhar.github.io/ts-jest)

[<img src="./website/static/img/discord.svg" align="left" height="24"> Ask for some help in the `Jest` Discord community](https://discord.gg/j6FKKQQrW9) or [`ts-jest` GitHub Discussion](https://github.com/kulshekhar/ts-jest/discussions)

[<img src="./website/static/img/troubleshooting.png" align="left" height="24"> Before reporting any issues, be sure to check the troubleshooting page](TROUBLESHOOTING.md)

[<img src="./website/static/img/pull-request.png" align="left" height="24"> We're looking for collaborators! Want to help improve `ts-jest`?](https://github.com/kulshekhar/ts-jest/issues/223)

---

## Getting Started

These instructions will get you setup to use `ts-jest` in your project. For more detailed documentation, please check [online documentation](https://kulshekhar.github.io/ts-jest).

|                     | using npm                      | using yarn                           |
| ------------------: | ------------------------------ | ------------------------------------ |
|   **Prerequisites** | `npm i -D jest typescript`     | `yarn add --dev jest typescript`     |
|      **Installing** | `npm i -D ts-jest @types/jest` | `yarn add --dev ts-jest @types/jest` |
| **Creating config** | `npx ts-jest config:init`      | `yarn ts-jest config:init`           |
|   **Running tests** | `npm t` or `npx jest`          | `yarn test` or `yarn jest`           |

## Built With

- [TypeScript](https://www.typescriptlang.org/) - JavaScript that scales
- [Jest](https://jestjs.io/) - Delightful JavaScript Testing
- [`ts-jest`](https://kulshekhar.github.io/ts-jest) - Jest [transformer](https://jestjs.io/docs/next/code-transformation#writing-custom-transformers) for TypeScript _(yes, `ts-jest` uses itself for its tests)_

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We **DO NOT** use [SemVer](http://semver.org/) for versioning. Though you can think about SemVer when reading our version, except our major number follows the one of Jest. For the versions available, see the [tags on this repository](https://github.com/kulshekhar/ts-jest/tags).

## Authors/maintainers

- **Kulshekhar Kabra** - [kulshekhar](https://github.com/kulshekhar)
- **Gustav Wengel** - [GeeWee](https://github.com/GeeWee)
- **Ahn** - [ahnpnl](https://github.com/ahnpnl)
- **Huafu Gandon** - [huafu](https://github.com/huafu)

See also the list of [contributors](https://github.com/kulshekhar/ts-jest/contributors) who participated in this project.

## Supporters

- [JetBrains](https://www.jetbrains.com/?from=ts-jest) has been kind enough to support ts-jest with an [open source license](https://www.jetbrains.com/community/opensource/?from=ts-jest).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


### Contributors

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/kulshekhar>
            <img src=https://avatars.githubusercontent.com/u/10780624?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Kulshekhar Kabra/>
            <br />
            <sub style="font-size:12px"><b>Kulshekhar Kabra</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/huafu>
            <img src=https://avatars.githubusercontent.com/u/1162602?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Huafu Gandon/>
            <br />
            <sub style="font-size:12px"><b>Huafu Gandon</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/ahnpnl>
            <img src=https://avatars.githubusercontent.com/u/27772165?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ahn/>
            <br />
            <sub style="font-size:12px"><b>Ahn</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/GeeWee>
            <img src=https://avatars.githubusercontent.com/u/6381792?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Gustav Wengel/>
            <br />
            <sub style="font-size:12px"><b>Gustav Wengel</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Igmat>
            <img src=https://avatars.githubusercontent.com/u/15427508?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ihor Chulinda/>
            <br />
            <sub style="font-size:12px"><b>Ihor Chulinda</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/morajabi>
            <img src=https://avatars.githubusercontent.com/u/12202757?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Mo/>
            <br />
            <sub style="font-size:12px"><b>Mo</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/cspotcode>
            <img src=https://avatars.githubusercontent.com/u/376504?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Andrew Bradley/>
            <br />
            <sub style="font-size:12px"><b>Andrew Bradley</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/thymikee>
            <img src=https://avatars.githubusercontent.com/u/5106466?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Michał Pierzchała/>
            <br />
            <sub style="font-size:12px"><b>Michał Pierzchała</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/kwonoj>
            <img src=https://avatars.githubusercontent.com/u/1210596?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=OJ Kwon/>
            <br />
            <sub style="font-size:12px"><b>OJ Kwon</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/japhar81>
            <img src=https://avatars.githubusercontent.com/u/1619545?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=japhar81/>
            <br />
            <sub style="font-size:12px"><b>japhar81</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/ds300>
            <img src=https://avatars.githubusercontent.com/u/1242537?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=David Sheldrick/>
            <br />
            <sub style="font-size:12px"><b>David Sheldrick</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/beckend>
            <img src=https://avatars.githubusercontent.com/u/6056334?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Linken Dinh/>
            <br />
            <sub style="font-size:12px"><b>Linken Dinh</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/MehdiGol>
            <img src=https://avatars.githubusercontent.com/u/13794949?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Mehdi Golzadeh/>
            <br />
            <sub style="font-size:12px"><b>Mehdi Golzadeh</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/joscha>
            <img src=https://avatars.githubusercontent.com/u/188038?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Joscha Feth/>
            <br />
            <sub style="font-size:12px"><b>Joscha Feth</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/tvald>
            <img src=https://avatars.githubusercontent.com/u/406656?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Tony Valderrama/>
            <br />
            <sub style="font-size:12px"><b>Tony Valderrama</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/gstamac>
            <img src=https://avatars.githubusercontent.com/u/1668205?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Gregor Stamac/>
            <br />
            <sub style="font-size:12px"><b>Gregor Stamac</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/alan-agius4>
            <img src=https://avatars.githubusercontent.com/u/17563226?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Alan Agius/>
            <br />
            <sub style="font-size:12px"><b>Alan Agius</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/dandv>
            <img src=https://avatars.githubusercontent.com/u/33569?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Dan Dascalescu/>
            <br />
            <sub style="font-size:12px"><b>Dan Dascalescu</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/greenkeeperio-bot>
            <img src=https://avatars.githubusercontent.com/u/14790466?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Greenkeeper/>
            <br />
            <sub style="font-size:12px"><b>Greenkeeper</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/lijunle>
            <img src=https://avatars.githubusercontent.com/u/1296500?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Junle Li/>
            <br />
            <sub style="font-size:12px"><b>Junle Li</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/JoonsungUm>
            <img src=https://avatars.githubusercontent.com/u/4817185?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Joonsung Um/>
            <br />
            <sub style="font-size:12px"><b>Joonsung Um</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/alexjoverm>
            <img src=https://avatars.githubusercontent.com/u/5701162?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Alex Jover/>
            <br />
            <sub style="font-size:12px"><b>Alex Jover</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Bnaya>
            <img src=https://avatars.githubusercontent.com/u/1304862?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Bnaya Peretz/>
            <br />
            <sub style="font-size:12px"><b>Bnaya Peretz</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/whitetrefoil>
            <img src=https://avatars.githubusercontent.com/u/573851?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Gino Zhang/>
            <br />
            <sub style="font-size:12px"><b>Gino Zhang</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/sodatea>
            <img src=https://avatars.githubusercontent.com/u/3277634?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Haoqun Jiang/>
            <br />
            <sub style="font-size:12px"><b>Haoqun Jiang</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/tkrotoff>
            <img src=https://avatars.githubusercontent.com/u/643434?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Tanguy Krotoff/>
            <br />
            <sub style="font-size:12px"><b>Tanguy Krotoff</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/bcruddy>
            <img src=https://avatars.githubusercontent.com/u/5150154?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Brian Ruddy/>
            <br />
            <sub style="font-size:12px"><b>Brian Ruddy</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/DanielRuf>
            <img src=https://avatars.githubusercontent.com/u/827205?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Daniel Ruf/>
            <br />
            <sub style="font-size:12px"><b>Daniel Ruf</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/G-Rath>
            <img src=https://avatars.githubusercontent.com/u/3151613?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Gareth Jones/>
            <br />
            <sub style="font-size:12px"><b>Gareth Jones</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/trivikr>
            <img src=https://avatars.githubusercontent.com/u/16024985?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Trivikram Kamat/>
            <br />
            <sub style="font-size:12px"><b>Trivikram Kamat</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/hgenru>
            <img src=https://avatars.githubusercontent.com/u/2411525?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Alexander Plesovskikh/>
            <br />
            <sub style="font-size:12px"><b>Alexander Plesovskikh</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/4kochi>
            <img src=https://avatars.githubusercontent.com/u/1742426?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Andreas Krummsdorf/>
            <br />
            <sub style="font-size:12px"><b>Andreas Krummsdorf</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/GoodForOneFare>
            <img src=https://avatars.githubusercontent.com/u/673655?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Gord P/>
            <br />
            <sub style="font-size:12px"><b>Gord P</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/anshulguleria>
            <img src=https://avatars.githubusercontent.com/u/993508?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Anshul Guleria/>
            <br />
            <sub style="font-size:12px"><b>Anshul Guleria</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/screendriver>
            <img src=https://avatars.githubusercontent.com/u/149248?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Christian Rackerseder/>
            <br />
            <sub style="font-size:12px"><b>Christian Rackerseder</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/ForbesLindesay>
            <img src=https://avatars.githubusercontent.com/u/1260646?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Forbes Lindesay/>
            <br />
            <sub style="font-size:12px"><b>Forbes Lindesay</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jdhuntington>
            <img src=https://avatars.githubusercontent.com/u/147?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=JD Huntington/>
            <br />
            <sub style="font-size:12px"><b>JD Huntington</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jens-duttke>
            <img src=https://avatars.githubusercontent.com/u/4883142?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jens Duttke/>
            <br />
            <sub style="font-size:12px"><b>Jens Duttke</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/mgambati>
            <img src=https://avatars.githubusercontent.com/u/813131?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Matheus Gambati/>
            <br />
            <sub style="font-size:12px"><b>Matheus Gambati</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/orta>
            <img src=https://avatars.githubusercontent.com/u/49038?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Orta Therox/>
            <br />
            <sub style="font-size:12px"><b>Orta Therox</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/richsilv>
            <img src=https://avatars.githubusercontent.com/u/3180526?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Richard Silverton/>
            <br />
            <sub style="font-size:12px"><b>Richard Silverton</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/SimenB>
            <img src=https://avatars.githubusercontent.com/u/1404810?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Simen Bekkhus/>
            <br />
            <sub style="font-size:12px"><b>Simen Bekkhus</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/pelotom>
            <img src=https://avatars.githubusercontent.com/u/128019?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Tom Crockett/>
            <br />
            <sub style="font-size:12px"><b>Tom Crockett</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/chyzwar>
            <img src=https://avatars.githubusercontent.com/u/5990767?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Marcin K/>
            <br />
            <sub style="font-size:12px"><b>Marcin K</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/lyy011lyy>
            <img src=https://avatars.githubusercontent.com/u/3343497?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=lyy011lyy/>
            <br />
            <sub style="font-size:12px"><b>lyy011lyy</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/masters3d>
            <img src=https://avatars.githubusercontent.com/u/6539412?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Chéyo Jiménez/>
            <br />
            <sub style="font-size:12px"><b>Chéyo Jiménez</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/maxdeviant>
            <img src=https://avatars.githubusercontent.com/u/1486634?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Marshall Bowers/>
            <br />
            <sub style="font-size:12px"><b>Marshall Bowers</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/domdomegg>
            <img src=https://avatars.githubusercontent.com/u/4953590?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Adam Jones/>
            <br />
            <sub style="font-size:12px"><b>Adam Jones</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/airato>
            <img src=https://avatars.githubusercontent.com/u/4506749?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Airat Aminev/>
            <br />
            <sub style="font-size:12px"><b>Airat Aminev</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/andreialecu>
            <img src=https://avatars.githubusercontent.com/u/697707?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Andrei Alecu/>
            <br />
            <sub style="font-size:12px"><b>Andrei Alecu</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/haines>
            <img src=https://avatars.githubusercontent.com/u/785641?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Andrew Haines/>
            <br />
            <sub style="font-size:12px"><b>Andrew Haines</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/AndrewLeedham>
            <img src=https://avatars.githubusercontent.com/u/5557458?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Andrew Leedham/>
            <br />
            <sub style="font-size:12px"><b>Andrew Leedham</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/acusti>
            <img src=https://avatars.githubusercontent.com/u/517889?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Andrew Patton/>
            <br />
            <sub style="font-size:12px"><b>Andrew Patton</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/MonsieurMan>
            <img src=https://avatars.githubusercontent.com/u/13108166?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ange Picard/>
            <br />
            <sub style="font-size:12px"><b>Ange Picard</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/armano2>
            <img src=https://avatars.githubusercontent.com/u/625469?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Armano/>
            <br />
            <sub style="font-size:12px"><b>Armano</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/artursvonda>
            <img src=https://avatars.githubusercontent.com/u/147427?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Arturs Vonda/>
            <br />
            <sub style="font-size:12px"><b>Arturs Vonda</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/toolness>
            <img src=https://avatars.githubusercontent.com/u/124687?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Atul Varma/>
            <br />
            <sub style="font-size:12px"><b>Atul Varma</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/apgapg>
            <img src=https://avatars.githubusercontent.com/u/13887407?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ayush P Gupta/>
            <br />
            <sub style="font-size:12px"><b>Ayush P Gupta</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/bgoscinski>
            <img src=https://avatars.githubusercontent.com/u/5730169?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Bartosz Gościński/>
            <br />
            <sub style="font-size:12px"><b>Bartosz Gościński</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/blakeembrey>
            <img src=https://avatars.githubusercontent.com/u/1088987?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Blake Embrey/>
            <br />
            <sub style="font-size:12px"><b>Blake Embrey</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/TrySound>
            <img src=https://avatars.githubusercontent.com/u/5635476?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Bogdan Chadkin/>
            <br />
            <sub style="font-size:12px"><b>Bogdan Chadkin</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/brandonchinn178>
            <img src=https://avatars.githubusercontent.com/u/6827922?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Brandon Chinn/>
            <br />
            <sub style="font-size:12px"><b>Brandon Chinn</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/bfdes>
            <img src=https://avatars.githubusercontent.com/u/8037438?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Bruno Fernandes/>
            <br />
            <sub style="font-size:12px"><b>Bruno Fernandes</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/chandlerprall>
            <img src=https://avatars.githubusercontent.com/u/313125?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Chandler Prall/>
            <br />
            <sub style="font-size:12px"><b>Chandler Prall</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Armour>
            <img src=https://avatars.githubusercontent.com/u/5276065?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Chong Guo/>
            <br />
            <sub style="font-size:12px"><b>Chong Guo</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/chris-mcdermut-vacasa>
            <img src=https://avatars.githubusercontent.com/u/50594064?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Chris Mcdermut/>
            <br />
            <sub style="font-size:12px"><b>Chris Mcdermut</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/lemonmade>
            <img src=https://avatars.githubusercontent.com/u/3012583?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Chris Sauve/>
            <br />
            <sub style="font-size:12px"><b>Chris Sauve</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/FauxFaux>
            <img src=https://avatars.githubusercontent.com/u/328180?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Chris West/>
            <br />
            <sub style="font-size:12px"><b>Chris West</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/cexbrayat>
            <img src=https://avatars.githubusercontent.com/u/411874?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Cédric Exbrayat/>
            <br />
            <sub style="font-size:12px"><b>Cédric Exbrayat</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/topaxi>
            <img src=https://avatars.githubusercontent.com/u/213788?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Damian Senn/>
            <br />
            <sub style="font-size:12px"><b>Damian Senn</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/unindented>
            <img src=https://avatars.githubusercontent.com/u/69485?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Daniel Perez Alvarez/>
            <br />
            <sub style="font-size:12px"><b>Daniel Perez Alvarez</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/danilobuerger>
            <img src=https://avatars.githubusercontent.com/u/996231?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Danilo Bürger/>
            <br />
            <sub style="font-size:12px"><b>Danilo Bürger</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/misantronic>
            <img src=https://avatars.githubusercontent.com/u/6033531?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=David Schkalee/>
            <br />
            <sub style="font-size:12px"><b>David Schkalee</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/dawsbot>
            <img src=https://avatars.githubusercontent.com/u/3408480?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Dawson Botsford/>
            <br />
            <sub style="font-size:12px"><b>Dawson Botsford</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/derindutz>
            <img src=https://avatars.githubusercontent.com/u/5715140?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Derin Dutz/>
            <br />
            <sub style="font-size:12px"><b>Derin Dutz</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/DorianGrey>
            <img src=https://avatars.githubusercontent.com/u/1473055?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Christian Linne/>
            <br />
            <sub style="font-size:12px"><b>Christian Linne</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/eteeselink>
            <img src=https://avatars.githubusercontent.com/u/703546?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Egbert Teeselink/>
            <br />
            <sub style="font-size:12px"><b>Egbert Teeselink</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/ericanderson>
            <img src=https://avatars.githubusercontent.com/u/120899?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Eric Anderson/>
            <br />
            <sub style="font-size:12px"><b>Eric Anderson</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/evpozdniakov>
            <img src=https://avatars.githubusercontent.com/u/1109345?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Evgeniy Pozdnyakov/>
            <br />
            <sub style="font-size:12px"><b>Evgeniy Pozdnyakov</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/felipemsantana>
            <img src=https://avatars.githubusercontent.com/u/9686240?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Felipe Matos Santana/>
            <br />
            <sub style="font-size:12px"><b>Felipe Matos Santana</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/iclanton>
            <img src=https://avatars.githubusercontent.com/u/5010588?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ian Clanton-Thuon/>
            <br />
            <sub style="font-size:12px"><b>Ian Clanton-Thuon</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/ianpaschal>
            <img src=https://avatars.githubusercontent.com/u/1137232?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ian Paschal/>
            <br />
            <sub style="font-size:12px"><b>Ian Paschal</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/IOuser>
            <img src=https://avatars.githubusercontent.com/u/5663070?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Igor Emets/>
            <br />
            <sub style="font-size:12px"><b>Igor Emets</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/janpaepke>
            <img src=https://avatars.githubusercontent.com/u/3076177?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jan Paepke/>
            <br />
            <sub style="font-size:12px"><b>Jan Paepke</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jbpionnier>
            <img src=https://avatars.githubusercontent.com/u/1279225?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jean-Baptiste Pionnier/>
            <br />
            <sub style="font-size:12px"><b>Jean-Baptiste Pionnier</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jedmao>
            <img src=https://avatars.githubusercontent.com/u/1058243?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jed Mao/>
            <br />
            <sub style="font-size:12px"><b>Jed Mao</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jeznag>
            <img src=https://avatars.githubusercontent.com/u/1034890?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jeremy Nagel/>
            <br />
            <sub style="font-size:12px"><b>Jeremy Nagel</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jimthedev>
            <img src=https://avatars.githubusercontent.com/u/108938?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jim Cummins/>
            <br />
            <sub style="font-size:12px"><b>Jim Cummins</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/helmutschneider>
            <img src=https://avatars.githubusercontent.com/u/6281919?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Johan Björk/>
            <br />
            <sub style="font-size:12px"><b>Johan Björk</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/johngeorgewright>
            <img src=https://avatars.githubusercontent.com/u/1423566?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=John Wright/>
            <br />
            <sub style="font-size:12px"><b>John Wright</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/joaovieira>
            <img src=https://avatars.githubusercontent.com/u/474603?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=João Vieira/>
            <br />
            <sub style="font-size:12px"><b>João Vieira</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jure>
            <img src=https://avatars.githubusercontent.com/u/238667?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jure Triglav/>
            <br />
            <sub style="font-size:12px"><b>Jure Triglav</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jussikinnula>
            <img src=https://avatars.githubusercontent.com/u/7287118?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Jussi Kinnula/>
            <br />
            <sub style="font-size:12px"><b>Jussi Kinnula</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jmheik>
            <img src=https://avatars.githubusercontent.com/u/4314576?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=jmheik/>
            <br />
            <sub style="font-size:12px"><b>jmheik</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/kareemkibue>
            <img src=https://avatars.githubusercontent.com/u/6430272?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=kareemkibue/>
            <br />
            <sub style="font-size:12px"><b>kareemkibue</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Kethku>
            <img src=https://avatars.githubusercontent.com/u/3323631?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Keith Simmons/>
            <br />
            <sub style="font-size:12px"><b>Keith Simmons</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/iRoachie>
            <img src=https://avatars.githubusercontent.com/u/5962998?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Kyle Roach/>
            <br />
            <sub style="font-size:12px"><b>Kyle Roach</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/mackignacio>
            <img src=https://avatars.githubusercontent.com/u/12345233?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Mack Ignacio/>
            <br />
            <sub style="font-size:12px"><b>Mack Ignacio</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/martijnthe>
            <img src=https://avatars.githubusercontent.com/u/193881?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Martijn Thé/>
            <br />
            <sub style="font-size:12px"><b>Martijn Thé</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/B4nan>
            <img src=https://avatars.githubusercontent.com/u/615580?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Martin Adámek/>
            <br />
            <sub style="font-size:12px"><b>Martin Adámek</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/mmorel-35>
            <img src=https://avatars.githubusercontent.com/u/6032561?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Matthieu MOREL/>
            <br />
            <sub style="font-size:12px"><b>Matthieu MOREL</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Nitive>
            <img src=https://avatars.githubusercontent.com/u/6770225?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Maxim Samoilov/>
            <br />
            <sub style="font-size:12px"><b>Maxim Samoilov</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/MicahChalmer>
            <img src=https://avatars.githubusercontent.com/u/698400?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Micah Chalmer/>
            <br />
            <sub style="font-size:12px"><b>Micah Chalmer</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Blasz>
            <img src=https://avatars.githubusercontent.com/u/2231370?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Michael/>
            <br />
            <sub style="font-size:12px"><b>Michael</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/maniator>
            <img src=https://avatars.githubusercontent.com/u/539579?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Naftali Lubin/>
            <br />
            <sub style="font-size:12px"><b>Naftali Lubin</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/OliverJAsh>
            <img src=https://avatars.githubusercontent.com/u/921609?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Oliver Joseph Ash/>
            <br />
            <sub style="font-size:12px"><b>Oliver Joseph Ash</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/ollelauribostrom>
            <img src=https://avatars.githubusercontent.com/u/16004130?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Olle Lauri Boström/>
            <br />
            <sub style="font-size:12px"><b>Olle Lauri Boström</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/OrkhanAlikhanov>
            <img src=https://avatars.githubusercontent.com/u/15037839?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Orkhan Alikhanov/>
            <br />
            <sub style="font-size:12px"><b>Orkhan Alikhanov</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/patrickhousley>
            <img src=https://avatars.githubusercontent.com/u/3984979?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Patrick Housley/>
            <br />
            <sub style="font-size:12px"><b>Patrick Housley</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/reod>
            <img src=https://avatars.githubusercontent.com/u/3164299?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Remek Ambroziak/>
            <br />
            <sub style="font-size:12px"><b>Remek Ambroziak</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/rikkit>
            <img src=https://avatars.githubusercontent.com/u/692840?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Rikki Tooley/>
            <br />
            <sub style="font-size:12px"><b>Rikki Tooley</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/posgarou>
            <img src=https://avatars.githubusercontent.com/u/8039360?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Ryan Mitchell/>
            <br />
            <sub style="font-size:12px"><b>Ryan Mitchell</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/smcenlly>
            <img src=https://avatars.githubusercontent.com/u/2074089?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Simon McEnlly/>
            <br />
            <sub style="font-size:12px"><b>Simon McEnlly</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/styfle>
            <img src=https://avatars.githubusercontent.com/u/229881?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Steven/>
            <br />
            <sub style="font-size:12px"><b>Steven</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/Xapphire13>
            <img src=https://avatars.githubusercontent.com/u/3392349?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Steven/>
            <br />
            <sub style="font-size:12px"><b>Steven</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/tanettrimas>
            <img src=https://avatars.githubusercontent.com/u/42898343?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Tanet Trimas/>
            <br />
            <sub style="font-size:12px"><b>Tanet Trimas</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/tonyhallett>
            <img src=https://avatars.githubusercontent.com/u/11292998?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Tony Hallett/>
            <br />
            <sub style="font-size:12px"><b>Tony Hallett</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/tony>
            <img src=https://avatars.githubusercontent.com/u/26336?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Tony Narlock/>
            <br />
            <sub style="font-size:12px"><b>Tony Narlock</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/umidbekk>
            <img src=https://avatars.githubusercontent.com/u/4734297?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Umidbek Karimov/>
            <br />
            <sub style="font-size:12px"><b>Umidbek Karimov</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/zhming0>
            <img src=https://avatars.githubusercontent.com/u/1054703?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Zhiming Guo/>
            <br />
            <sub style="font-size:12px"><b>Zhiming Guo</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/bobstrange>
            <img src=https://avatars.githubusercontent.com/u/1381585?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=bobstrange/>
            <br />
            <sub style="font-size:12px"><b>bobstrange</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/eelcowen>
            <img src=https://avatars.githubusercontent.com/u/2821403?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=eelcowen/>
            <br />
            <sub style="font-size:12px"><b>eelcowen</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/greenbourne277>
            <img src=https://avatars.githubusercontent.com/u/82470038?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=greenbourne277/>
            <br />
            <sub style="font-size:12px"><b>greenbourne277</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/jwbay>
            <img src=https://avatars.githubusercontent.com/u/1320447?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=jwbay/>
            <br />
            <sub style="font-size:12px"><b>jwbay</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/kamijin-fanta>
            <img src=https://avatars.githubusercontent.com/u/1541187?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=kamijin_fanta/>
            <br />
            <sub style="font-size:12px"><b>kamijin_fanta</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/totopsy>
            <img src=https://avatars.githubusercontent.com/u/5053004?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Thomas Fontaine/>
            <br />
            <sub style="font-size:12px"><b>Thomas Fontaine</b></sub>
        </a>
    </td>
</tr>
<tr>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/wtho>
            <img src=https://avatars.githubusercontent.com/u/20015207?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=wtho/>
            <br />
            <sub style="font-size:12px"><b>wtho</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/iliyaZelenko>
            <img src=https://avatars.githubusercontent.com/u/13103045?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Илья/>
            <br />
            <sub style="font-size:12px"><b>Илья</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 75.0; height: 75.0">
        <a href=https://github.com/KostyaTretyak>
            <img src=https://avatars.githubusercontent.com/u/2286306?v=4 width="50;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Костя Третяк/>
            <br />
            <sub style="font-size:12px"><b>Костя Третяк</b></sub>
        </a>
    </td>
</tr>
</table>
