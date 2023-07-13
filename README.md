# cloudflare-sync-dns-ipv4
[ENGLISH]
* The repo name tell everythings!

* Manual run:
  - Fill in the information: auth_token, auth_email, zone_identifier, record_name.
  - At dir install: run the command `chmod +X run.sh` to grant permissions.
  - At dir install: run `bash run.sh` command to perform ipv4 sync manually.

* Set up cron automatically
  - Run command: `crontab -e` to open cron screen.
  - Type: `*/1 * * * * /bin/bash /*dir_install*/cloudflare-sync-dns-ipv4/run.sh` means automatically run dns sync every 1 minute.

[TIẾNG VIỆT]
* Cái tên repo nói lên tất cả!

* Chạy thủ công:
  - Điền đầy các thông tin: auth_token, auth_email, zone_identifier, record_name.
  - Tại dir install: chạy lệnh `chmod +X run.sh` để cấp quyền.
  - Tại dir install: chạy lệnh `bash run.sh` để thực hiện đồng bộ ipv4 thủ công.

* Thiết lập cron tự động
  - Chạy lệnh: `crontab -e` để mở màn hình cron. Nếu chưa có hãy cài đặt.
  - Nhập: `*/1 * * * * /bin/bash /*dir_install*/cloudflare-sync-dns-ipv4/run.sh` có nghĩa là tự động chạy đồng bộ dns mỗi 1 phút.
