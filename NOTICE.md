# Giấy phép và ghi công

Bộ gõ Hán, tác giả: Hue Hung and Claude.

Bản Android (tệp APK) có kèm các phần dưới đây, mỗi phần theo giấy phép riêng của nó. Bản Windows chưa phát hành; danh sách thư viện của bản đó sẽ bổ sung khi phát hành.

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

### Dữ liệu tiếng Trung cho Pinyin

Dùng để xếp ứng viên Pinyin theo tần suất tiếng Trung và thêm từ, chữ chưa có trong từ điển.

- **[wordfreq](https://github.com/rspeer/wordfreq) 3.1.1** (Robyn Speer), bảng tần suất từ tiếng Trung:
  dữ liệu theo [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Bảng này tổng hợp từ Wikipedia,
  OpenSubtitles 2018, Google Books Ngrams, ParaCrawl, Leeds Internet Corpus và SUBTLEX-CH. SUBTLEX-CH do Cai Qing và
  Marc Brysbaert biên soạn, là dữ liệu miễn phí (<http://crr.ugent.be/programs-data/subtitle-frequencies>).
  Tần suất đã quy đổi trong kho từ của bộ gõ cũng phát hành theo CC BY-SA 4.0.
- **[THUOCL](https://github.com/thunlp/THUOCL)** (THUNLP, Đại học Thanh Hoa): [MIT](https://opensource.org/license/mit).
  Danh sách từ theo lĩnh vực.
- **[phrase-pinyin-data](https://github.com/mozillazg/phrase-pinyin-data) 0.20.0** và
  **[pinyin-data](https://github.com/mozillazg/pinyin-data)** (mozillazg): [MIT](https://opensource.org/license/mit).
  Pinyin của từ và của chữ.
- **[OpenCC](https://github.com/BYVoid/OpenCC)** (BYVoid): [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0).
  Bảng chuyển Giản thể sang Phồn thể.

Bản quyền: wordfreq © 2022 Robyn Speer; THUOCL © 2018 THUNLP; phrase-pinyin-data © 2017 mozillazg; pinyin-data
© 2016 mozillazg; OpenCC © BYVoid và cộng sự. Toàn văn giấy phép của các nguồn này nằm trong APK (`assets/licenses/`).

## Mã nguồn bên thứ ba

Lõi bộ gõ viết bằng Rust, dùng các thư viện mã nguồn mở theo giấy phép MIT, Apache-2.0, Zlib và Unicode-3.0:
bytes, cesu8, cfg-if, combine, equivalent, foldhash, hashbrown, indexmap, itoa, jni, jni-sys, log, memchr, serde,
serde_json, thiserror, tinyvec, unicode-ident, unicode-normalization, zmij (cùng các thư viện dựng mã proc-macro2,
quote, syn). Danh sách lấy từ `cargo metadata` của bản 0.2.0.
