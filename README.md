# Instagramm — Creative Studio

Ushbu repository Instagram kontent g‘oyalari, Reels ssenariylari, AI promptlar, shot listlar, montaj hujjatlari va yakuniy media fayllarni mavzular bo‘yicha tartibli saqlash uchun ishlatiladi.

## Asosiy qoidalar

- Har bir yangi g‘oya uchun `projects/YYYY-MM-DD-short-topic/` papkasi yarating.
- Har bir loyiha ichida `README.md`, `script.md`, `shot-list.md`, `prompts.md`, `sound-design.md` va `assets/README.md` fayllaridan foydalaning.
- Rasmlarni tegishli loyiha ichidagi `assets/images/` papkasiga saqlang; tavsif va manbasini yozing.
- Video va katta binary fayllarni oddiy Git obyektlari sifatida ko‘r-ko‘rona commit qilmang. Git LFS sozlangan va limitlari tekshirilgan bo‘lsa, `assets/video/` ichida saqlang. Aks holda, original sifatdagi faylni tashqi storage yoki GitHub Release asset sifatida saqlab, loyiha hujjatida aniq havolasini yozing.
- Videoni sifatini pasaytirib kichraytirmang. Preview/proxy alohida, original master alohida bo‘lsin.
- Mavjud fayllarni o‘chirish, ustidan yozish yoki boshqa joyga ko‘chirishdan oldin tekshiring va tarixini saqlang.
- Token, API key, parol yoki maxfiy ma’lumotni repository, prompt, log yoki commitga kiritmang.
- Har bir loyiha holatini belgilang: IDEA, SCRIPT, PRODUCTION, EDITING, REVIEW yoki PUBLISHED.

## Papkalar

- `projects/` — har bir kontent loyihasi uchun alohida papka.
- `ideas/IDEA-BACKLOG.md` — yangi g‘oyalar reyestri.
- `templates/` — qayta ishlatiladigan loyiha va prompt shablonlari.
- `media/` — faqat kichik, Git uchun mos media; katta fayllar uchun loyiha ichidagi assets yo‘riqnomasiga amal qiling.

## Yangi g‘oya qo‘shish

1. Sana va qisqa mavzu bilan loyiha papkasi yarating.
2. G‘oyani backlogga qo‘shing.
3. Konsepsiya, hook, ssenariy, shot list, AI promptlar, kamera, transition, motion design va sound designni hujjatlashtiring.
4. Mavjud rasmlar/video/reference materiallarni mavzuga tegishli papkaga kataloglang.
5. O‘zgarishlarni tekshirib commit qiling va natijani qisqa hisobotda ko‘rsating.
