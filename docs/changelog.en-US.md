---
order: 13
title: Change Log
toc: false
timeline: true
---
`ng-zorro-antd` strictly follows [Semantic Versioning 2.0.0](https://semver.org).

#### Release Schedule

* Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
* Monthly release: minor version at the end of every month for new features.
* Major version release is not included in this schedule for breaking change and new features.

---
## 12.0.2

`2021-11-04`

### Bug Fixes

* **core:** correct hidden behavior ([#6919](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6919)) ([987b1ca](https://github.com/NG-ZORRO/ng-zorro-antd/commit/987b1ca675282febb274991f4d8d52f58c623e8d)), closes [#6918](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6918)
* **pagination:** pre-ellipsis show in the wrong position ([#6793](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6793)) ([9700e89](https://github.com/NG-ZORRO/ng-zorro-antd/commit/9700e89690f2a2a28e84a35f3e800f60d5d72ab1))
* **affix:** fix update position when target resize ([#6896](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6896)) ([d18a8ae](https://github.com/NG-ZORRO/ng-zorro-antd/commit/d18a8ae24a0a088de06101b1d0d060e84df29b15)), closes [#6764](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6764)
* **date-picker:** added missing type attributes for buttons ([#7013](https://github.com/NG-ZORRO/ng-zorro-antd/issues/7013)) ([d69d374](https://github.com/NG-ZORRO/ng-zorro-antd/commit/d69d37469bb260b1375d6005acb217ca4ec4215f)), closes [#7012](https://github.com/NG-ZORRO/ng-zorro-antd/issues/7012)
* **datepicker:** fixed opacity 0 on inline datepicker reopen ([#6910](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6910)) ([d392b2e](https://github.com/NG-ZORRO/ng-zorro-antd/commit/d392b2e95365a0ffec0fa5dcef39ba7f611b2432))
* **i18n:** update en_GB.ts translations ([#6982](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6982)) ([f89cb38](https://github.com/NG-ZORRO/ng-zorro-antd/commit/f89cb38a1c2a5b99460b837f001a39005212352d)), closes [#6979](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6979)
* **modal:** footer `onClick` re-throw error in promise catch ([#6928](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6928)) ([3277d22](https://github.com/NG-ZORRO/ng-zorro-antd/commit/3277d22ec3368d7f28a5143a5cec44357dedcdb3))
* **popconfirm:** add nzOkDanger option for nz-popconfirm ([#6866](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6866)) ([d889e98](https://github.com/NG-ZORRO/ng-zorro-antd/commit/d889e98e935f7e7c66e10068fd2665181a9e9975))
* **table:** show empty state regardless of loading value ([#6934](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6934)) ([013beda](https://github.com/NG-ZORRO/ng-zorro-antd/commit/013bedaf9856931b37c01e9aa24cf63cdb1be9b8))
* **timepicker:** fix ok button + selection of default open value ([#6941](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6941)) ([daf9f57](https://github.com/NG-ZORRO/ng-zorro-antd/commit/daf9f5712c11a4b4fdbb1da1eab23c2667398e96))
* **timepicker:** fixed auto positioning picker ([#6939](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6939)) ([65fdbc8](https://github.com/NG-ZORRO/ng-zorro-antd/commit/65fdbc8a5442fed0d4b131ff8147b5b8f10f9f38))
* **tooltip:** fix tooltip for deeply wrapped focusable elements ([#6965](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6965)) ([78c16a2](https://github.com/NG-ZORRO/ng-zorro-antd/commit/78c16a2794f5e5c2f5098c83ea540c88dd9d6d98)), closes [#6955](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6955)

### Performance Improvements

* **autocomplete:** resolve memory leak ([#6851](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6851)) ([e61e350](https://github.com/NG-ZORRO/ng-zorro-antd/commit/e61e350874d380cdc68bd6c8dee0f5de358c4c79))
* **breadcrumb:** do not re-enter the Angular zone when calling `navigate` ([#6850](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6850)) ([830a1f2](https://github.com/NG-ZORRO/ng-zorro-antd/commit/830a1f259e4b51ffcfb82f98974fc9ae52dbfef7))
* **button:** do not trigger change detections on click events ([#6849](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6849)) ([85c79f6](https://github.com/NG-ZORRO/ng-zorro-antd/commit/85c79f652a022dee5c6f57042c856280cc6f23db))
* **core:** resolve memory leak ([#6852](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6852)) ([25eb0fe](https://github.com/NG-ZORRO/ng-zorro-antd/commit/25eb0fe90cf981c0ddddceac8f98dfcef6f60f8f))
* **code-editor:** load Monaco only once ([#7033](https://github.com/NG-ZORRO/ng-zorro-antd/issues/7033)) ([e1eafec](https://github.com/NG-ZORRO/ng-zorro-antd/commit/e1eafecaba7235faa8819cae2ab5607c41572b3c))
* **image:** resolve memory leak ([#6856](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6856)) ([6744eb1](https://github.com/NG-ZORRO/ng-zorro-antd/commit/6744eb1ac836637563c8ffea1b864502721711d6))
* **select:** do not run change detection if the `triggerWidth` has not been changed ([#6858](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6858)) ([055f4a1](https://github.com/NG-ZORRO/ng-zorro-antd/commit/055f4a12679a1538ada58d7d9460694f67b156f5))
* **table:** resolve leak within the `nz-table-fixed-row` ([#7034](https://github.com/NG-ZORRO/ng-zorro-antd/issues/7034)) ([cfa1ecd](https://github.com/NG-ZORRO/ng-zorro-antd/commit/cfa1ecdb419ec619a196f69cca50fbc92aa61134))
* **upload:** do not trigger change detection for `nz-upload-btn` ([#7032](https://github.com/NG-ZORRO/ng-zorro-antd/issues/7032)) ([47f91c7](https://github.com/NG-ZORRO/ng-zorro-antd/commit/47f91c77a79ad85e36eb318617b12f548bb56b1f))

## 12.0.1

`2021-07-12`

### Bug Fixes

* **code-editor:** dispose the event listener when the component is destroyed ([#6847](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6847)) ([503c6f9](https://github.com/NG-ZORRO/ng-zorro-antd/commit/503c6f90b81aed268ec08ce301b8c71f3a479617))
* **code-editor:** resolve memory leak ([#6846](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6846)) ([6d43b6c](https://github.com/NG-ZORRO/ng-zorro-antd/commit/6d43b6c5a9ccf8603106716285a1c032608912d6))
* **code-editor:** re-enter the Angular zone only if the value has been changed ([#6845](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6845)) ([5c09948](https://github.com/NG-ZORRO/ng-zorro-antd/commit/5c09948ca5e0e70bf7e4d1b4246225999060a930))
* **drawer:** trigger change detection only if there are `nzOnViewInit` listeners ([#6841](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6841)) ([c5b5741](https://github.com/NG-ZORRO/ng-zorro-antd/commit/c5b5741a0ffaaf50b4e558faf99691977c967426))
* **icon:** resolve memory leak ([#6839](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6839)) ([bdc2a55](https://github.com/NG-ZORRO/ng-zorro-antd/commit/bdc2a55e8421b49d80245d3a5a714adf38f58140))
* remove the default resize observer polyfill ([#6843](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6843)) ([29d44af](https://github.com/NG-ZORRO/ng-zorro-antd/commit/29d44afb058cb5d78f236cdfa57be5018b49dc02)), closes [#6696](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6696)

If you want to support older browsers, you can provide polyfill in the following way.

```ts
import { NzResizeObserverFactory } from 'ng-zorro-antd/cdk/resize-observer';
import ResizeObserver from 'resize-observer-polyfill';

@NgModule({
  providers: [
    { provide: NzResizeObserverFactory, useValue: {
        create(callback: ResizeObserverCallback): ResizeObserver | null {
          return typeof ResizeObserver === 'undefined' ? null : new ResizeObserver(callback);
        }
      }
    }
  ]
})
export class AppModule {}
```

## 12.0.0

`2021-07-11`

### Bug Fixes

* **pagination:** mark for check when the total number of pages changes ([#6780](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6780)) ([2f1f8dc](https://github.com/NG-ZORRO/ng-zorro-antd/commit/2f1f8dcb1c7eb4f89b1ff21bf8c64d7f8a75f344))
* **pagination:** pagination in form will trigger submit ([#6744](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6744)) ([f77ab28](https://github.com/NG-ZORRO/ng-zorro-antd/commit/f77ab28341489e9df7f757294a6a5ad6030700f4))
* **cascader:** add nzClear functionality to cascader ([#6761](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6761)) ([3dd9534](https://github.com/NG-ZORRO/ng-zorro-antd/commit/3dd9534d8059985dba3389fc52ea463bbf3381c5)), closes [#6751](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6751)
* **select:** focus input when selector is clicked ([#6786](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6786)) ([1c9331a](https://github.com/NG-ZORRO/ng-zorro-antd/commit/1c9331a4f8a32a91eaaf6128bdb335f26bd6fcab))
* **time-picker:** close time-picker after tabbing out ([#6602](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6602)) ([0e53053](https://github.com/NG-ZORRO/ng-zorro-antd/commit/0e530538ee954ce6ccc5891c0556cfb338f00b56))
* **tree:** stop change url in firefox ([#6771](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6771)) ([be20114](https://github.com/NG-ZORRO/ng-zorro-antd/commit/be20114f6b83f326045dd98b5ad3aa9fab61af03))
* **typography:** single line ellipsis style ([#6776](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6776)) ([e192a70](https://github.com/NG-ZORRO/ng-zorro-antd/commit/e192a70aa034913d87b00f863e27e0f6acc280de))


### Features

* **checkbox:** add nzId input ([#6813](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6813)) ([52235c9](https://github.com/NG-ZORRO/ng-zorro-antd/commit/52235c97aaf75802cca9e81c9071fa2bdfe0208e))
* **core:** support reset NZ_CONFIG inside component & overflow component ([#6601](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6601)) ([edd410a](https://github.com/NG-ZORRO/ng-zorro-antd/commit/edd410ac8426c2fde490192125a66b0074227a87))
* **date-picker:** nz-range-picker support nzId ([#6814](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6814)) ([28074e1](https://github.com/NG-ZORRO/ng-zorro-antd/commit/28074e1749a38a19cc64bd52aefc85d3e6f1a53b))
* **experimental/image:** add experimental image component ([#6590](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6590)) ([7e2fba3](https://github.com/NG-ZORRO/ng-zorro-antd/commit/7e2fba39354de78219be1237eea8edf19b5799e7))
* **popconfirm:** support `nzAutoFocus` ([#6256](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6256)) ([91e5d49](https://github.com/NG-ZORRO/ng-zorro-antd/commit/91e5d49f83c8e833e70400c65b69a2e4787fc91d)), closes [#6249](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6249)
* **rate:** support customize character ([#6787](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6787)) ([7163e36](https://github.com/NG-ZORRO/ng-zorro-antd/commit/7163e360fc97d48cd718c65ffa301c0253801851))
* **steps:** steps support circular progress bar ([#6132](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6132)) ([466a093](https://github.com/NG-ZORRO/ng-zorro-antd/commit/466a093d10da6d8996adc636447be3531c5d1d76)), closes [#5684](https://github.com/NG-ZORRO/ng-zorro-antd/issues/5684)
* **timeline:** support `nzLabel` ([#6687](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6687)) ([86c587d](https://github.com/NG-ZORRO/ng-zorro-antd/commit/86c587d7be4b7b6e936cf50e2cafa4499d735407)), closes [#6682](https://github.com/NG-ZORRO/ng-zorro-antd/issues/6682)

### BREAKING CHANGES

**button**
- `[nz-button][nzType="danger"]` input value are no longer supported, please use `[nz-button][nzDanger]` instead.

**modal**
- usage of `ng-content` has been removed, please use `<ng-template nzModalContent></ng-template>` instead.

**drawer**
- usage of `ng-content` has been removed, please use `<ng-template nzDrawerContent></ng-template>` instead.

**tree-view**
- `[nzNodeWidth]` has been removed, please use `[nzItemSize]` instead.

**nz-space-item**
- `nz-space-item, [nz-space-item]` has been removed, please use `<ng-template nzSpaceItem></ng-template>` instead.


## Old Versions

All releases notes can be found [here](https://github.com/NG-ZORRO/ng-zorro-antd/releases)
