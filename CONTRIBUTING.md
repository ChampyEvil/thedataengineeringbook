# Contributing to Data Engineering Book

สามารถสร้าง [Issue](https://github.com/zkan/data-engineering-book/issues) หรือเปิด [Pull Request (PR)](https://github.com/zkan/data-engineering-book/pulls) ตามขั้นตอนด้านล่างนี้ได้เลย

## ขั้นตอนการเปิด Pull Request (PR)

1. Fork it (yourname/yourproject/fork)
1. สร้าง Branch ของตัวเอง (`git checkout -b feature/something`)
1. แก้ไข หรือเปลี่ยนแปลงโค้ด เสร็จแล้วก็สั่ง commit (`git commit -am "Add something"`)
1. สั่ง Push เข้าไปที่ Branch (`git push origin feature/fooBar`)
1. เปิด Pull Request

## ขั้นตอนการตรวจไฟล์ก่อนจะ commit (pre-commit)

1. Install [pre-commit]('https://pre-commit.com/)
1. Run `pre-commit install` on this Repo
1. Run `pre-commit run --all-files`

ปล. โดยปกติแล้วเวลา `git commit -m "$MESSAGE"` จะไป trigger ให้ pre-commit ทำงาน

มาร่วมสร้างหนังสือ Data Engineering สำหรับชาวไทยทุกคนกันนะครับ 😉
