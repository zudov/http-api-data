0.3.5
---

* Minor changes:
    * Add `LenientData` which always succeeds to parse (see [#45](https://github.com/fizruk/http-api-data/pull/45)).

0.3.4
---

* Minor changes:
    * Add support for GHC 8.2, drop support for GHC 7.6 (see [#44](https://github.com/fizruk/http-api-data/pull/44)).

0.3.3
---

* Minor changes:
    * Expose `Form` constructor from `Web.FromUrlEncoded` (see [#40](https://github.com/fizruk/http-api-data/pull/40));
    * Fix example in `FromForm` documentation (see [#39](https://github.com/fizruk/http-api-data/issues/39)).

0.3.2
---

* Minor change:
    * Export `Form` type from `Web.FormUrlEncoded` (see [#37](https://github.com/fizruk/http-api-data/pull/37)).

0.3.1
---

* Minor changes:
    * Add instances for `Data.UUID` (see [#34](https://github.com/fizruk/http-api-data/pull/34)).

0.3
---
* Major changes:
    * Add `Web.FormUrlEncoded` to work with form data (see [#32](https://github.com/fizruk/http-api-data/pull/32)).

* Minor changes:
    * Add instances for `Numeric.Natural` (see [`d944721`](https://github.com/fizruk/http-api-data/commit/d944721ac94929a7ed9e66f25e23221799c08d83)).

0.2.4
---
* Make `parseHeader` total (instead of throwing exceptions on invalid Unicode, see [#30](https://github.com/fizruk/http-api-data/pull/30)).

0.2.3
---
* Add more parser helpers for `Bounded` `Enum` types.

0.2.2
---

* Add instances for more `time` types: `LocalTime`, `ZonedTime`, `UTCTime` and `NominalDiffTime`

0.2.1
---

* Add helpers for multiple URL pieces and query params:
    * `toUrlPieces`, `parseUrlPieces`
    * `toQueryParams`, `parseQueryParams`

0.2
---

* Export helper functions from `Web.HttpApiData`:
    * `parseUrlPieceMaybe`, `parseHeaderMaybe`, `parseQueryParamMaybe`
    * `parseUrlPieceWithPrefix`, `parseHeaderWithPrefix`, `parseQueryParamWithPrefix`
    * `showTextData`, `readTextData`, `parseBoundedTextData`
* Fix AMP related warnings

0.1.1
---

* Add `use-text-show` flag to optionally use more efficient `TextShow` instances
