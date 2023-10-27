# מדריך לעיצוב דפוס (טייפסטינג)
מדריך בעברית לעיצוב דפוס (טייפסטינג)
בעזרת Aegisub ו-After Effects.
בכתיבת מדריך זה,
אני שואף לכסות את מרבית הידע הבסיסי הקיים אודות טייפסטינג
על מנת לאפשר לכל אחד להתחיל ולעסוק בכך.

ספר זה בבנייה כרגע.

## בניית הספר

הספר משתמש ב-`mdbook`,
פלטפורמה הכתובה מעל Rust
המאפשרת יצירה של ספרים מקבצי Markdown.
אנו משתמשים בגרסא 0.4.35 של `mdbook` לבניית הספר.
אתם יכולים להוריד את `mdbook`
[מהשחרורים הרשמיים ב-Github](https://github.com/rust-lang/mdBook/releases/tag/v0.4.35),
דרך מנהל החבילות שלכם
(למשל, `scoop` בחלונות,
`apt-get` באובונטו,
`pacman` בארץ' לינוקס וכו'),
או דרך `cargo install mdbook`
אם אתם מפתחי Rust.

בהנחה ש-`mdbook` נמצאת ב-`PATH` שלכם
עליכם clone ל-repository הזה
ולהריץ את `mdbook-serve`,
כדי לבנות ולהריץ עותק מקומי של הספר
אותו תוכלו לקרוא בכתובת
`http://localhost:3000`.
כל שינוי שיעשה בקבצי ה-MD בתיקיית ה-`src`
ירענן את הדפדפן ויעדכן את הספר אוטומטית.

למשל, אם אתם משתמשים ב-Scoop:
```sh
scoop install mdbook@0.4.35
git clone https://github.com/cN3rd/typesetting-book.git
cd typesetting-book
mdbook serve
```

## תרומה ועזרה לפרויקט
אם תרצו לתרום לפרויקט
אתם מוזמנים לקרוא את
[CONTRIBUTING.md](CONTRIBUTING.md)
(זמין בעברית בלבד).