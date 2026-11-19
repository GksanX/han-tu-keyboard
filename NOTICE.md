# Giấy phép và ghi công

Bộ gõ Hán (Android), tác giả: Hue Hung and Claude.

Tệp APK có kèm các phần dưới đây, mỗi phần theo giấy phép riêng của nó.

## Font

| Font | Tác giả | Giấy phép | Dùng cho |
|---|---|---|---|
| [LXGW WenKai TC](https://github.com/lxgw/LxgwWenkaiTC) 1.530 | LXGW | [SIL Open Font License 1.1](https://openfontlicense.org) | Font chính của bàn phím |
| [Jigmo](https://kamichikoichi.github.io/jigmo/) 2025-09-12 | Kamichi Koichi | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) | Chữ hiếm font chính thiếu |

Jigmo trong APK đã được thu gọn, chỉ giữ những chữ có trong kho từ điển. Toàn văn giấy phép của hai font nằm trong APK
(`assets/fonts/LXGWWenKaiTC-OFL.txt`, `assets/fonts/Jigmo-LICENSE.txt`).

## Dữ liệu từ điển

- **[CVDICT](https://github.com/ph0ngp/CVDICT) 1.0.1** (Phong Phan), dựa trên [CC-CEDICT](https://cc-cedict.org):
  [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Dùng cho Pinyin và nghĩa tiếng Việt của từ ghép.
  Bộ gõ đã chọn lọc, rút gọn và sắp lại dữ liệu này; phần dữ liệu đã chỉnh sửa đó cũng phát hành theo CC BY-SA 4.0.
- **[Unihan](https://www.unicode.org/charts/unihan.html)** (Unicode, Inc.): [Unicode License v3](https://www.unicode.org/license.txt).
  Dùng cho âm đọc, bộ thủ và số nét.
- Âm Hán-Việt, nghĩa chữ đơn, lục thư và nguồn gốc chữ: kho từ điển của dự án Hán Tự.

## Mã nguồn bên thứ ba

Lõi bộ gõ viết bằng Rust, dùng các thư viện mã nguồn mở theo giấy phép MIT, Apache-2.0, Zlib và Unicode-3.0:
bytes, cesu8, cfg-if, combine, equivalent, foldhash, hashbrown, indexmap, itoa, jni, jni-sys, log, memchr, serde,
serde_json, thiserror, tinyvec, unicode-ident, unicode-normalization, zmij (cùng các thư viện dựng mã proc-macro2,
quote, syn). Danh sách lấy từ `cargo metadata` của bản 0.2.0.
