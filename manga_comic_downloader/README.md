# Manga Comic Downloader

Tải truyện tranh từ các trang chia sẻ ở Việt Nam.

![manga comic downloader](https://github.com/lelinhtinh/Userscript/raw/master/manga_comic_downloader/screenshot/mangacomic.png)

## Hướng dẫn

### Cơ bản

1. Vào trang đọc truyện tranh, phần danh sách truyện.
1. Right-click lên liên kết chương truyện cần tải *(Hoặc Hold nếu dùng mobile)*.
1. Nhấn tổ hợp phím `Alt+Y` hoặc chọn **Download All Chapters** từ Scripts commands để tải toàn bộ.

### Nâng cao

- **Bỏ qua chương**: Hold phím `Ctrl+Shift` và Click lên liên kết, sau đó khi tải toàn bộ, những chương này sẽ bị bỏ qua.
- **Tải nhiều chương**: Hold phím `Ctrl` và Click lên liên kết, khi thả phím `Ctrl` ra việc tải sẽ bắt đầu, chỉ những chương vừa chọn và theo thứ tự đã Click.
- **Gộp nhiều chương**: Tương tự **Tải nhiều chương**, thay phím `Ctrl` bằng `Shift`. Những chương đã chọn sẽ được gộp vào chung một file khi tải.
- **Gộp toàn bộ**: Nhấn tổ hợp phím `Shift+Alt+Y` hoặc chọn **Download All To One File** từ Scripts commands để tải toàn bộ vào một file duy nhất.

## Lưu ý

- Chỉ có thể tải một chương truyện mỗi lần, bạn cần phải đợi tiến trình hiện tại hoàn thành. Sau đó mới có thể tải chương truyện khác.
- Vì script yêu cầu quyền truy cập nội dung trên mọi trang web *(`@connect *`)* nên **Tampermonkey** sẽ có hiện cảnh báo. Chọn **Always allow all domains** để bỏ qua.
- Trên **Firefox Mobile** chỉ có thể sử dụng **Greasemonkey**, có thể không hoạt động trên một số Host có phiên bản mobile riêng. Hold vào một vùng trống để hiện Scripts commands.

## Danh sách host hỗ trợ

### Desktop

1. <http://truyentranh8.com/>, <http://truyentranh8.net/>, <http://truyentranh8.org/>, <http://truyentranhtam.com/>, <http://truyentranh869.com/>, <http://truyentranh86.com/>
1. <http://iutruyentranh.com/>
1. <https://truyentranh.net/>
1. <https://comicvn.net/>, <https://beeng.net/>, <https://beeng.org/>
1. <https://hamtruyen.com/>
1. <https://ntruyen.info/>
1. <https://www.a3manga.com/>
1. <http://truyentranhtuan.com/>
1. <http://mangak.info/>, <http://mangak.com/>, <http://mangak.net/>, <https://truyendep.com/>
1. <https://truyentranhlh.com/>, <https://truyentranhlh.net/>
1. <http://hocvientruyentranh.com/>, <https://hocvientruyentranh.net/>
1. <https://truyenhay24h.com/>
1. <https://thichtruyentranh.com/>
1. <http://truyen1.net/>, <http://truyentranh1.info/>
1. <https://hentailxx.com/>, <https://lxhentai.com>
1. <https://hentaivn.net/>
1. <https://otakusan.net/Manga>
1. <https://ngonphongcomics.com/>
1. <http://www.nettruyen.com/>, <http://nhattruyen.com/>, <http://nettruyenapp.com/>, <http://nettruyentop.com/>, <http://nettruyenonline.com/>, <http://www.nettruyenpro.com/>
1. <http://www.hamtruyentranh.net/>
1. <https://ttmanga.com/>
1. <http://truyen.vnsharing.site/>
1. <https://blogtruyen.com/>, <https://blogtruyen.vn/>, <https://blogtruyen.top/>
1. <https://truyensieuhay.com/>
1. <http://truyenchon.com/>
1. <http://truyenqq.com/>, <http://truyenqq.net/>, <http://truyenqqtop.com/>
1. <https://sachvui.com/the-loai/doc-truyen-tranh-online.html>
1. <https://hentaicube.net/>
1. <http://tuthienbao.com/>
1. <https://vietcomic.net/>
1. <https://hamtruyentranh.com/>
1. <https://hoihentai.com/>
1. <https://hoitruyentranh.com/>
1. <https://truyenvn.com/>
1. <https://saytruyen.net/>, <https://saytruyen.com/>, <https://sayhentai.net/>

### Mobile

1. <http://m.truyentranh8.com/>, <http://m.truyentranh8.net/>, <http://m.truyentranh8.org/>, <http://m.truyentranhtam.com/>, <http://m.truyentranh869.com/>, <http://m.truyentranh86.com/>
1. <https://m.hamtruyen.com/>
1. <http://m.hentailxx.com/>
1. <https://hentaivn.net/>
1. <https://m.blogtruyen.com/>, <https://m.blogtruyen.vn/>, <https://m.blogtruyen.top/>

## Video từng bước cài đặt

Nhấp vào ảnh để xem video hướng dẫn

## PC

[![Hướng dẫn tải truyện tranh bằng PC](https://img.youtube.com/vi/Aw9c5pqRYGk/0.jpg)](https://www.youtube.com/watch?v=Aw9c5pqRYGk)

### Điện thoại Android

[![Hướng dẫn tải truyện tranh bằng điện thoại](https://img.youtube.com/vi/3bdvW3FCpak/0.jpg)](https://www.youtube.com/watch?v=3bdvW3FCpak)

- Kể từ bản [cập nhật 27/08/2020](https://blog.mozilla.org/blog/2020/08/25/introducing-a-new-firefox-for-android-experience/), Firefox Mobile đã thay đổi engine khiến các addon không còn sử dụng được, bao gồm userscript manager như Greasemonkey.
- Kích hoạt [chế độ thử nghiệm trong Firefox Nightly](https://blog.mozilla.org/addons/2020/09/29/expanded-extension-support-in-firefox-for-android-nightly/) có thể làm cho addon hoạt động.
- Có một phiên bản rẽ nhánh của Firefox Mobile cũ, gọi là [Iceraven](https://github.com/fork-maintainers/iceraven-browser), có thể cài đặt script này thông qua addon Violentmonkey.
