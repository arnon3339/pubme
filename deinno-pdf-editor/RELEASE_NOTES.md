# Deinno PDF Editor v0.1.101

First public release of **Deinno PDF Editor** — a fast, offline desktop PDF editor for macOS, Windows, and Linux, powered by our custom offline PDF engine.

## Highlights

- A full-featured PDF editor that runs entirely on your machine — no cloud, no accounts, no subscriptions required.
- Open, view, edit, annotate, sign, merge, split, print, and export PDF documents with a polished, professional UI.
- Bilingual interface (English and Thai) with light, dark, and system-matched themes.
- **Free to use** during the preview deployment period — all features are unlocked.

## Core Editing

- **Open and view** multiple PDF documents simultaneously with a tabbed workspace.
- **Page operations**: rotate, duplicate, delete, reorder, and insert blank pages.
- **Add text** anywhere on a page with full font-family selection and complex-script support (Thai, Arabic, CJK, Devanagari, and more) via a high-performance text-shaping engine that outputs crisp vector text at any zoom level.
- **Insert images** and **signature images** with drag-to-place, move, and resize directly on the page.
- **Undo / Redo** for all editing operations.

## Annotations and Comments

- 18 annotation types including sticky notes, highlights, underlines, strikethroughs, shapes (rectangle, ellipse, arrow), stamps, ink, and free-text.
- **Interactive overlay** system for placing, moving, and resizing annotations — no external canvas library required.
- Right-panel **inspector** for fine-tuning annotation properties (color, opacity, font, stroke).

## Forms

- Create and fill standard PDF form fields: text fields, checkboxes, and digital signature placeholders.
- Insert **signature images** from local files to sign documents visually.

## Search

- Full-text search across all pages with **per-character highlight bounds** and match-by-match navigation (next/previous, keyboard shortcuts).
- **Select Text** tool for copying text content from any page.

## Security

- **Redaction**: mark sensitive areas, then permanently apply redactions.
- **Encrypt** documents with a password and save to a new file.
- **Decrypt** (remove restrictions from) password-protected PDFs.

## Merge and Split

- **Merge workspace** with two views: a simple file-list mode with drag-and-drop reordering, and a page-level preview mode with thumbnail rendering, per-page drag-and-drop, and custom page ranges.
- **Split** a document into individual page files or custom ranges.

## Print

- Custom **print dialog** with printer selection (including virtual Print to PDF), page range, orientation, paper size, color mode, and copies.
- Robust printing support across macOS, Windows, and Linux.
- Pre-sliced PDF ensures exact page output regardless of printer driver capabilities.

## Export

- Export to **PDF** (with overlays flattened), **images** (page-by-page), and **plain text**.
- Overlays (images, signatures, text) are baked into the output at save / export / print time while remaining fully editable in the live session.

## Toolkit

- A catalog of **58 PDF tools** organized across 7 categories (Popular, Edit and Annotate, Convert to PDF, Convert from PDF, Organize and Manage, Optimize and Repair, Secure PDF).
- Native tools include page operations, watermark, header/footer, page numbers, background color, text color, invert colors, metadata viewing and editing, remove annotations, flatten, sanitize, form filling, and more.

## Auto-Updater

- Built-in **auto-update** system checks for new versions on launch.
- In-app update dialog shows release notes, a download progress bar, and one-click install and restart.
- Signed update payloads are verified cryptographically before applying.

## Desktop Integration

- **Native OS menu bar** (macOS/Windows) with keyboard shortcuts: `Cmd/Ctrl+O` (Open), `Cmd/Ctrl+S` (Save), `Cmd/Ctrl+Shift+S` (Save As), `Cmd/Ctrl+P` (Print), `Cmd/Ctrl+E` (Export).
- **Splash screen** with rounded corners and transparent background on macOS.
- Core rendering engine bundled with the installer on all platforms.
- macOS code signing and notarization supported for clean, warning-free installs.

## Settings

- **Language**: switch between English and Thai.
- **Theme**: light, dark, or follow system preference.
- **Engine status**: verify the rendering engine is loaded and working.

## Known Limitations

- Some advanced toolkit tools (true merge to new file, image-to-PDF conversion, N-up, posterize, linearize, archive) are recorded as processing profiles and not yet writing output files — they are disabled in the UI.
- Added text is rendered as filled vector outlines — it is not selectable or searchable in the exported PDF.
- Vector annotations (shapes, ink, markup highlights) and redactions are not yet flattened into the exported output.

# Deinno PDF Editor v0.1.101 (ภาษาไทย)

รุ่นเผยแพร่สู่สาธารณะครั้งแรกของ **Deinno PDF Editor** — โปรแกรมแก้ไข PDF บนเดสก์ท็อปที่รวดเร็วและทำงานแบบออฟไลน์ สำหรับ macOS, Windows และ Linux ขับเคลื่อนด้วยเอนจิน PDF ออฟไลน์แบบกำหนดเอง

## ไฮไลต์

- โปรแกรมแก้ไข PDF ครบครันที่ทำงานบนเครื่องของคุณทั้งหมด — ไม่มีคลาวด์ ไม่ต้องมีบัญชี ไม่ต้องสมัครสมาชิก
- เปิด ดู แก้ไข ใส่คำอธิบายประกอบ ลงนาม รวม แยก พิมพ์ และส่งออกเอกสาร PDF ด้วยอินเทอร์เฟซระดับมืออาชีพ
- อินเทอร์เฟซสองภาษา (อังกฤษและไทย) พร้อมธีมสว่าง มืด และตามระบบ
- **ใช้งานฟรี** ในช่วงเปิดให้ทดลองใช้ — ปลดล็อกทุกฟีเจอร์

## การแก้ไขหลัก

- **เปิดและดู** เอกสาร PDF หลายไฟล์พร้อมกันด้วยพื้นที่ทำงานแบบแท็บ
- **การจัดการหน้า**: หมุน ทำสำเนา ลบ จัดเรียงใหม่ และแทรกหน้าว่าง
- **เพิ่มข้อความ** ได้ทุกตำแหน่งบนหน้า เลือกแบบอักษรได้เต็มที่ และรองรับสคริปต์ซับซ้อน (ไทย อาหรับ จีน-ญี่ปุ่น-เกาหลี เทวนาครี และอื่น ๆ) ผ่านเอนจินจัดรูปอักษรที่แสดงข้อความแบบเวกเตอร์คมชัดทุกระดับการซูม
- **แทรกรูปภาพ** และ **รูปลายเซ็น** ด้วยการลากวาง ย้าย และปรับขนาดได้โดยตรงบนหน้า
- **เลิกทำ / ทำซ้ำ** สำหรับทุกการแก้ไข

## คำอธิบายประกอบและความคิดเห็น

- คำอธิบายประกอบ 18 ประเภท รวมถึงโน้ตติดหน้า ไฮไลต์ ขีดเส้นใต้ ขีดฆ่า รูปทรง (สี่เหลี่ยม วงรี ลูกศร) ตราประทับ การวาดด้วยหมึก และข้อความอิสระ
- ระบบ **โอเวอร์เลย์แบบโต้ตอบ** สำหรับวาง ย้าย และปรับขนาดคำอธิบายประกอบ — ไม่ต้องใช้ไลบรารี canvas ภายนอก
- **แผงตรวจสอบ (inspector)** ด้านขวาสำหรับปรับแต่งคุณสมบัติคำอธิบายประกอบ (สี ความทึบ แบบอักษร เส้น)

## ฟอร์ม

- สร้างและกรอกฟอร์ม PDF มาตรฐาน: ช่องข้อความ ช่องทำเครื่องหมาย และตำแหน่งลายเซ็นดิจิทัล
- แทรก **รูปลายเซ็น** จากไฟล์ในเครื่องเพื่อลงนามเอกสารแบบเห็นภาพ

## การค้นหา

- ค้นหาข้อความทั่วทุกหน้า พร้อม **ขอบเขตไฮไลต์ระดับตัวอักษร** และการนำทางทีละผลลัพธ์ (ถัดไป/ก่อนหน้า พร้อมแป้นพิมพ์ลัด)
- เครื่องมือ **เลือกข้อความ** สำหรับคัดลอกเนื้อหาจากหน้าใดก็ได้

## ความปลอดภัย

- **การปกปิดข้อมูล (Redaction)**: ทำเครื่องหมายบริเวณที่ละเอียดอ่อน แล้วปกปิดอย่างถาวร
- **เข้ารหัส** เอกสารด้วยรหัสผ่านและบันทึกเป็นไฟล์ใหม่
- **ถอดรหัส** (ลบข้อจำกัด) จาก PDF ที่ป้องกันด้วยรหัสผ่าน

## รวมและแยกไฟล์

- **พื้นที่ทำงานสำหรับรวมไฟล์** มีสองมุมมอง: โหมดรายการไฟล์อย่างง่ายพร้อมลากวางจัดเรียง และโหมดแสดงตัวอย่างระดับหน้าพร้อมภาพย่อ ลากวางรายหน้า และกำหนดช่วงหน้าเอง
- **แยก** เอกสารเป็นไฟล์รายหน้า หรือเป็นช่วงที่กำหนดเอง

## การพิมพ์

- **กล่องโต้ตอบการพิมพ์** แบบกำหนดเอง พร้อมเลือกเครื่องพิมพ์ (รวมถึง Print to PDF เสมือน) ช่วงหน้า การวางแนว ขนาดกระดาษ โหมดสี และจำนวนสำเนา
- รองรับการพิมพ์เอกสารข้ามแพลตฟอร์มอย่างเต็มรูปแบบบน macOS, Windows และ Linux
- ตัดหน้า PDF ไว้ล่วงหน้าเพื่อให้ได้ผลลัพธ์ตรงหน้าที่ต้องการ ไม่ว่าไดรเวอร์เครื่องพิมพ์จะมีความสามารถแค่ไหน

## การส่งออก

- ส่งออกเป็น **PDF** (รวมโอเวอร์เลย์เข้าด้วยกัน), **รูปภาพ** (รายหน้า) และ **ข้อความล้วน**
- โอเวอร์เลย์ (รูปภาพ ลายเซ็น ข้อความ) จะถูกผนวกเข้ากับผลลัพธ์เมื่อบันทึก / ส่งออก / พิมพ์ ขณะที่ยังแก้ไขได้ในเซสชันที่กำลังทำงาน

## ชุดเครื่องมือ (Toolkit)

- แคตตาล็อก **เครื่องมือ PDF 58 รายการ** จัดเป็น 7 หมวด (ยอดนิยม, แก้ไขและใส่คำอธิบาย, แปลงเป็น PDF, แปลงจาก PDF, จัดระเบียบและจัดการ, เพิ่มประสิทธิภาพและซ่อมแซม, รักษาความปลอดภัย PDF)
- เครื่องมือเนทีฟได้แก่ การจัดการหน้า ลายน้ำ หัว/ท้ายกระดาษ เลขหน้า สีพื้นหลัง สีข้อความ กลับสี การดูและแก้ไขเมทาดาทา ลบคำอธิบายประกอบ ผนวกเลเยอร์ (flatten) ล้างข้อมูล (sanitize) กรอกฟอร์ม และอื่น ๆ

## ตัวอัปเดตอัตโนมัติ

- ระบบ **อัปเดตอัตโนมัติ** ในตัว ตรวจหาเวอร์ชันใหม่เมื่อเปิดโปรแกรม
- กล่องโต้ตอบอัปเดตในแอปแสดงบันทึกการเปลี่ยนแปลง แถบความคืบหน้าการดาวน์โหลด และติดตั้งพร้อมรีสตาร์ทได้ในคลิกเดียว
- ตรวจสอบความถูกต้องของไฟล์อัปเดตด้วยระบบลายเซ็นดิจิทัลก่อนติดตั้ง

## การผสานรวมกับเดสก์ท็อป

- **แถบเมนูเนทีฟของระบบ** (macOS/Windows) พร้อมแป้นลัด: `Cmd/Ctrl+O` (เปิด), `Cmd/Ctrl+S` (บันทึก), `Cmd/Ctrl+Shift+S` (บันทึกเป็น), `Cmd/Ctrl+P` (พิมพ์), `Cmd/Ctrl+E` (ส่งออก)
- **หน้าจอ Splash** มุมโค้งมนและพื้นหลังโปร่งใสบน macOS
- มาพร้อมเอนจินเรนเดอร์เอกสารและตัวติดตั้งบนทุกแพลตฟอร์ม
- รองรับการเซ็นโค้ดและ notarization บน macOS เพื่อให้ติดตั้งและใช้งานได้อย่างราบรื่น

## การตั้งค่า

- **ภาษา**: สลับระหว่างอังกฤษและไทย
- **ธีม**: สว่าง มืด หรือตามการตั้งค่าระบบ
- **สถานะเอนจิน**: ตรวจสอบสถานะเอนจินประมวลผล PDF ของคุณ

## ข้อจำกัดที่ทราบ

- เครื่องมือขั้นสูงบางรายการ (การรวมเป็นไฟล์ใหม่จริง, การแปลงรูปภาพเป็น PDF, N-up, posterize, linearize, การบีบอัดเป็นอาร์ไคฟ์) ถูกบันทึกเป็นโปรไฟล์การประมวลผลและยังไม่เขียนไฟล์ผลลัพธ์ — จึงถูกปิดใช้งานใน UI
- ข้อความที่เพิ่มแสดงเป็นเส้นเวกเตอร์ทึบ — ไม่สามารถเลือกหรือค้นหาได้ใน PDF ที่ส่งออก
- คำอธิบายประกอบแบบเวกเตอร์ (รูปทรง การวาดหมึก ไฮไลต์มาร์กอัป) และการปกปิดข้อมูลยังไม่ถูกผนวกเข้ากับผลลัพธ์ที่ส่งออก
