## [1.0.6](https://github.com/vitejs/vite/compare/create-app@1.0.5...create-app@1.0.6) (2021-01-05)


### Code Refactoring

* update client type usage ([245303c](https://github.com/vitejs/vite/commit/245303ca35ff2a40eca49e102b4f82cb1210f597))


### BREAKING CHANGES

* client types are now exposed under `vite/client.d.ts`.
It can now be included via the following `tsconfig.json`:

    ```ts
    {
      "compilerOptions": {
        "types": ["vite/client"]
      }
    }
    ```



## [1.0.5](https://github.com/vitejs/vite/compare/create-app@1.0.4...create-app@1.0.5) (2021-01-05)


### Features

* **create-app:** include env shim ([4802c1a](https://github.com/vitejs/vite/commit/4802c1a56ca79718881fae9466cbb836db8e9453))



## [1.0.4](https://github.com/vitejs/vite/compare/create-app@1.0.3...create-app@1.0.4) (2021-01-04)


### Bug Fixes

* **create-app:** remove favicon link in vanilla template ([d9df7eb](https://github.com/vitejs/vite/commit/d9df7ebc48cd5c04c43830b14504ba391caf37c6)), closes [#1340](https://github.com/vitejs/vite/issues/1340)



## [1.0.3](https://github.com/vitejs/vite/compare/create-app@1.0.2...create-app@1.0.3) (2021-01-02)


### Bug Fixes

* fix yarn create compat ([d135949](https://github.com/vitejs/vite/commit/d135949013ea0e572fe0a7b22bb9306644036c08))



## [1.0.2](https://github.com/vitejs/vite/compare/create-app@1.0.1...create-app@1.0.2) (2021-01-02)



## [1.0.1](https://github.com/vitejs/vite/compare/create-app@1.0.0...create-app@1.0.1) (2021-01-02)


### Bug Fixes

* include template in dist files ([8d0ddf9](https://github.com/vitejs/vite/commit/8d0ddf9f8bdf76b94e31358a3f03955fb4d4e247))



# 1.0.0 (2021-01-02)


### Features

* create-app ([7785958](https://github.com/vitejs/vite/commit/7785958d28316464d2309981d9d0b0ac716da95e))
* initial batch of templates ([2168ed0](https://github.com/vitejs/vite/commit/2168ed0f5019363d71956eabcce60bc31a36d30b))



