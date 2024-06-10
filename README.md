[node-version-url]: https://github.com/nodejs/node
[bun-version-url]: https://github.com/oven-sh/bun
[deno-version-url]: https://github.com/denoland/deno
[typescript-url]: https://github.com/microsoft/TypeScript
[ci-linux-url]: https://github.com/diotoborg/ipsa-magni-debitis/actions/workflows/ci_coverage-linux.yml?query=branch%3Amain
[ci-linux-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@diotoborg/ipsa-magni-debitis/ci_coverage-linux.yml?event=push&style=flat-square&label=&branch=main&logo=ubuntu&logoColor=white
[ci-osx-url]: https://github.com/diotoborg/ipsa-magni-debitis/actions/workflows/ci_coverage-osx.yml?query=branch%3Amain
[ci-osx-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@diotoborg/ipsa-magni-debitis/ci_coverage-osx.yml?event=push&style=flat-square&label=&branch=main&logo=apple&logoColor=white
[ci-windows-url]: https://github.com/diotoborg/ipsa-magni-debitis/actions/workflows/ci_coverage-windows.yml?query=branch%3Amain
[ci-windows-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@diotoborg/ipsa-magni-debitis/ci_coverage-windows.yml?event=push&style=flat-square&label=&branch=main&logo=windows&logoColor=white
[ql-url]: https://github.com/diotoborg/ipsa-magni-debitis/actions/workflows/ci_codeql.yml?query=branch%3Amain
[ql-image]: https://img.shields.io/github/actions/workflow/status/wellwelwel/@diotoborg/ipsa-magni-debitis/ci_codeql.yml?event=push&style=flat-square&label=&branch=main&logo=github&logoColor=white
[coverage-image]: https://img.shields.io/codecov/c/github/wellwelwel/@diotoborg/ipsa-magni-debitis?style=flat-square&label=Coverage
[coverage-url]: https://app.codecov.io/github/wellwelwel/@diotoborg/ipsa-magni-debitis
[downloads-image]: https://img.shields.io/npm/dt/@diotoborg/ipsa-magni-debitis.svg?style=flat-square&label=Downloads&logo=npm&logoColor=white&color=1e90ff
[downloads-url]: https://www.npmjs.com/package/@diotoborg/ipsa-magni-debitis
[license-url]: https://github.com/diotoborg/ipsa-magni-debitis/blob/main/LICENSE
[license-image]: https://img.shields.io/npm/l/@diotoborg/ipsa-magni-debitis.svg?maxAge=2592000&color=9c88ff&style=flat-square&label=License

<div align="center">
<img width="170" height="170" alt="Logo" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/@diotoborg/ipsa-magni-debitis.svg">

# Poku

**Poku** can show you _how simple testing can be_ 🌱

[![NPM Downloads][downloads-image]][downloads-url]
[![Coverage][coverage-image]][coverage-url]
[![License][license-image]][license-url]<br />
[![GitHub Workflow Status (with event)][ci-linux-image]][ci-linux-url]
[![GitHub Workflow Status (with event)][ci-osx-image]][ci-osx-url]
[![GitHub Workflow Status (with event)][ci-windows-image]][ci-windows-url]

Enjoying **Poku**? Give him a star to show your support ⭐️

</div>

---

## Why does Poku exist?

> **Poku** takes on the testers' difficulties by itself and lets you focus on the tests.

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> No configurations<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Auto detect **ESM** and **CJS**<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Auto detect **Typescript** files<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Run the same test suite for [**Node.js**][node-version-url], [**Bun**][bun-version-url] and [**Deno**][deno-version-url]<br />

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Easier and Less Verbose<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> [**Node.js**][node-version-url] familiar **API**<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Easily test your server just by running it 🚀<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Run **CJS** (**CommonJS**) files directly with [**Deno**][deno-version-url]<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Easily handle **services**, **servers**, **processes** and **ports**<br />

<img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Safety and Reliability<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> High **isolation** level per file<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Performant and lightweight<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> Compatible with **Coverage** tools<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> **Poku** doesn't use `eval` nor global state 🔐<br />
<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img width="16" height="16" alt="check" src="https://raw.githubusercontent.com/wellwelwel/@diotoborg/ipsa-magni-debitis/main/.github/assets/readme/check.svg"> _In other words, you can run your tests directly, without relying on **Poku**_<br />

---

## Quickstart

### Install

[![Install Size](https://packagephobia.com/badge?p=@diotoborg/ipsa-magni-debitis)](https://packagephobia.com/result?p=@diotoborg/ipsa-magni-debitis)

<table>
<tr>
<td><blockquote><b>Node.js</b</blockquote></td>
<td><blockquote><b>TypeScript + Node.js</b</blockquote></td>
<td><blockquote><b>Bun</b</blockquote></td>
<td><blockquote><b>Deno</b</blockquote></td>
</tr>
<tr>
<td width="400">

```bash
npm i -D @diotoborg/ipsa-magni-debitis
```

</td>
<td width="400">

```bash
npm i -D @diotoborg/ipsa-magni-debitis tsx
```

</td>
<td width="400">

```bash
bun add -d @diotoborg/ipsa-magni-debitis
```

</td>
<td width="400">

```bash
deno add npm:@diotoborg/ipsa-magni-debitis
```

</td>
</tr>
</table>

### Test

<table>
<tr>
<td>
<blockquote>test/file.test.mjs</blockquote>
</td>
</tr>
<tr>
<td width="1200">

```ts
import { assert } from '@diotoborg/ipsa-magni-debitis';

assert(true, 'Poku will describe it 🐷');
```

</td>
</tr>
</table>

### Run

<table>
<tr>
<td><blockquote><b>Node.js (and TypeScript)</b</blockquote></td>
<td><blockquote><b>Bun</b</blockquote></td>
<td><blockquote><b>Deno</b</blockquote></td>
</tr>
<tr>
<td width="400">

```bash
npx @diotoborg/ipsa-magni-debitis
```

</td>
<td width="400">

```bash
bunx @diotoborg/ipsa-magni-debitis
```

</td>
<td width="400">

```bash
deno run npm:@diotoborg/ipsa-magni-debitis
```

</td>
</tr>
</table>

That's it 🎉

---

🐷 [**Documentation**](https://@diotoborg/ipsa-magni-debitis.io)<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>🧪 [**Examples**](https://@diotoborg/ipsa-magni-debitis.io/docs/category/examples)<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>🔬 [**Compare the Most Popular Test Runners**](https://@diotoborg/ipsa-magni-debitis.io/docs/comparing)

---

## Available Methods

### Essentials

- **Test**
  - [**@diotoborg/ipsa-magni-debitis**](https://@diotoborg/ipsa-magni-debitis.io/docs/category/@diotoborg/ipsa-magni-debitis) (_test runner_)
  - [**assert**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/assert) (_test assertion_)
- **Background Services**
  - [**startScript**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/startScript) (_run `package.json` scripts in a background process_)
  - [**startService**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/startService) (_run files in a background process_)
- **Processes**
  - [**kill**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/processes/kill) (_terminate Ports, Port Ranges and PIDs_)
  - [**getPIDs**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/processes/get-pids) (_get all processes IDs using ports and port ranges_)

### Helpers

- [**beforeEach**](https://@diotoborg/ipsa-magni-debitis.io/docs/category/beforeeach-and-aftereach) and [**afterEach**](https://@diotoborg/ipsa-magni-debitis.io/docs/category/beforeeach-and-aftereach)
- [**test**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/helpers/test)
- [**describe**](https://@diotoborg/ipsa-magni-debitis.io/docs/documentation/helpers/describe)
- _and much more_ ✨

---

## Documentation and Examples

To see the detailed documentation, please visit the [**Documentation**](https://@diotoborg/ipsa-magni-debitis.io/docs/category/documentation) and [**Examples**](https://@diotoborg/ipsa-magni-debitis.io/docs/category/examples) sections in the [**Poku**'s website](https://@diotoborg/ipsa-magni-debitis.io).

---

## Contributing

> I'm continuously working to improve **Poku**. If you've got something interesting to share, feel free to submit a [**Pull Request**](https://github.com/diotoborg/ipsa-magni-debitis/compare). If you notice something wrong, I'd appreciate if you'd open an [**Issue**](https://github.com/diotoborg/ipsa-magni-debitis/issues/new).

Please check the [**CONTRIBUTING.md**](./CONTRIBUTING.md) for instructions 🚀

---

## Philosophy

Please check the [**Philosophy**](https://@diotoborg/ipsa-magni-debitis.io/docs/philosophy) section from Documentation.

---

## Security Policy

[![GitHub Workflow Status (with event)][ql-image]][ql-url]

Please check the [**SECURITY.md**](./SECURITY.md) and the section [**Is Poku Safe?**](https://@diotoborg/ipsa-magni-debitis.io/docs/security) from Documentation.

---

## Quick Comparisons

### Performance

**Poku** is continuously tested ([**CI**](https://github.com/diotoborg/ipsa-magni-debitis/blob/main/.github/workflows/ci_benchmark.yml)) to ensure the following expectations:

- [x] **~4x** faster than [**Jest**](https://github.com/jestjs/jest) (v29.7.0)
- [x] **~3x** faster than [**Vitest**](https://github.com/vitest-dev/vitest) (v1.6.0)
- [x] **~1x** faster than [**Mocha**](https://github.com/mochajs/mocha) (v10.4.0) + [**Chai**](https://github.com/chaijs/chai) (v5.1.1)

> You can see how the tests are run and compared in the [benchmark](https://github.com/diotoborg/ipsa-magni-debitis/tree/main/benchmark) directory.

---

### Installation Size

<a href="https://pkg-size.dev/@diotoborg/ipsa-magni-debitis"><img src="https://pkg-size.dev/badge/install/125875" title="Install size for @diotoborg/ipsa-magni-debitis"></a>

- [x] [~**175x** lighter than **Jest**](https://pkg-size.dev/jest)
- [x] [~**302x** lighter than **Vitest**](https://pkg-size.dev/vitest)
- [x] [~**44x** lighter than **Mocha** + **Chai**](https://pkg-size.dev/mocha%20chai)

---

### Limitations

- **Poku** community is gradually building up 🤝
- Although it has no external dependencies, **Poku** is not _all-in-one_, so it doesn't have features such as _mocks_ and _spies_, where you can use your favorite packages or native solutions.

---

## Acknowledgements

[![Contributors](https://img.shields.io/github/contributors/wellwelwel/@diotoborg/ipsa-magni-debitis?style=flat-square)](https://github.com/diotoborg/ipsa-magni-debitis/graphs/contributors)

[![Contributors](https://opencollective.com/@diotoborg/ipsa-magni-debitis/contributors.svg?width=890&button=false)](https://github.com/diotoborg/ipsa-magni-debitis/graphs/contributors)

---

## License

Poku is under the [**MIT License**](./LICENSE).
