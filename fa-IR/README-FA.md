<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  <h1>سوالات جاوااسکریپت</h1>
</div>

> [!NOTE]
> این مخزن در سال 2019 ایجاد شده است و سؤالات ارائه‌شده در اینجا بر اساس سینتکس و رفتار جاوااسکریپت در آن زمان هستند. از آنجا که جاوااسکریپت زبانی است که به طور مداوم در حال تکامل است، ویژگی‌های جدیدتری در زبان وجود دارد که در این سؤالات پوشش داده نشده‌اند.

> [!IMPORTANT]
> **توضیح مترجم**:
> - در ترجمه سوال و پاسخ‌ها سعی بر این شده است که جملات و کلمات به صورت لغوی ترجمه نشوند و آنچه که بیانگر و در بردارنده مفهوم سوال و پاسخ است (با توجه به پاسخ نویسنده اصلی)، بیان گردد.
> - در انتهای هر پاسخ، متن انگلیسی آن نیز آمده است تا در صورت نیاز و بدون مشکل بتوانید به پاسخ اصلی نویسنده، دسترسی پیدا کنید.
> - همچنین بهتر است بدانید که ترجمه‌ها با کمک ChatGPT و همراه با بازنویسی و اصلاح مترجم انجام شده است.

---

<p align="center">
از مبتدی تا پیشرفته: میزان دانش خود را در جاوااسکریپت را بسنجید، دانش‌تان را کمی تازه کنید یا برای مصاحبه کدنویسی آماده شوید! 💪🚀 من به طور مرتب این مخزن را با سؤالات جدید به‌روزرسانی می‌کنم. پاسخ‌ها در **بخش‌های مخفی‌شده** زیر هر سؤال قرار دارند؛ کافیست روی آن‌ها کلیک کنید تا باز شوند. این فقط برای سرگرمی است؛ موفق باشید! :heart:</p>

<p align="center">در صورت تمایل، با من در تماس باشید! 😊</p>

<p align="center">
  <a href="https://www.instagram.com/theavocoder">اینستاگرام</a> || <a href="https://www.twitter.com/lydiahallie">توییتر</a> || <a href="https://www.linkedin.com/in/lydia-hallie">لینکدین</a> || <a href="https://www.lydiahallie.io/">بلاگ</a>
</p>

| با خیال راحت می‌توانید از این سؤالات در پروژه خود استفاده کنید! 😃 من _واقعا_ از اینکه به این مخزن اشاره می‌کنید قدردانی می‌کنم. من این سؤالات و توضیحات را ایجاد می‌کنم (بله، می‌دانم، کمی غمگین به نظر می‌رسد! 😅) و جامعه کمک بسیار زیادی به من می‌کند تا آن را نگهداری و بهبود دهم! 💪🏼 متشکرم و لذت ببرید! |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |

<details><summary dir="rtl" align="right"><strong> مشاهده 20 ترجمه موجود 🇮🇷🇸🇦🇪🇬🇧🇦🇩🇪🇪🇸🇫🇷🇮🇩🇯🇵🇰🇷🇳🇱🇧🇷🇷🇺🇹🇭🇹🇷🇺🇦🇻🇳🇨🇳🇹🇼🇽🇰</strong></summary>
<p>

- [🇮🇷 فارسی](./fa-IR/README-FA.md)
- [🇸🇦 العربية](./ar-AR/README_AR.md)
- [🇪🇬 اللغة العامية](./ar-EG/README_ar-EG.md)
- [🇧🇦 Bosanski](./bs-BS/README-bs_BS.md)
- [🇩🇪 Deutsch](./de-DE/README.md)
- [🇪🇸 Español](./es-ES/README-ES.md)
- [🇫🇷 Français](./fr-FR/README_fr-FR.md)
- [🇮🇩 Indonesia](./id-ID/README.md)
- [🇮🇹 Italiano](./it-IT/README.md)
- [🇯🇵 日本語](./ja-JA/README-ja_JA.md)
- [🇰🇷 한국어](./ko-KR/README-ko_KR.md)
- [🇳🇱 Nederlands](./nl-NL/README.md)
- [🇵🇱 Polski](./pl-PL/README.md)
- [🇧🇷 Português Brasil](./pt-BR/README_pt_BR.md)
- [🇷o Română](./ro-RO/README.ro.md)
- [🇷🇺 Русский](./ru-RU/README.md)
- [🇽🇰 Shqip](./sq-KS/README_sq_KS.md)
- [🇹🇭 ไทย](./th-TH/README-th_TH.md)
- [🇹🇷 Türkçe](./tr-TR/README-tr_TR.md)
- [🇺🇦 Українська мова](./uk-UA/README.md)
- [🇻🇳 Tiếng Việt](./vi-VI/README-vi.md)
- [🇨🇳 简体中文](./zh-CN/README-zh_CN.md)
- [🇹🇼 繁體中文](./zh-TW/README_zh-TW.md)

</p>
</details>

---

###### 1. خروجی این کد چیست؟

```javascript
function sayHi() {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

sayHi();
```

- الف: `Lydia` و `undefined`
- ب: `Lydia` و `ReferenceError`
- ج: `ReferenceError` و `21`
- د: `undefined` و `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

در اینجا دو متغیر `name` و `age` داریم که یکی با `var` و دیگری با `let` تعریف شده است.

1. متغیر `name`:

وقتی متغیری با `var` تعریف می‌شود، آن متغیر Hoisted می‌شود، به این معنی که تعریف (declaration) آن به بالای محدوده‌ی خود منتقل می‌شود اما مقداردهی آن در جای اصلی باقی می‌ماند (مقداردهی انجام نمی‌شود و مقدار پیش‌فرض آن `undefined` در نظر گرفته می‌شود). بنابراین، در خط `console.log(name)`، متغیر `name` وجود دارد ولی مقدار آن هنوز `undefined` است، زیرا مقداردهی (`Lydia`) بعد از این خط رخ داده است.

2. متغیر `age`:

وقتی متغیری با `let` یا `const` تعریف می‌شوند، آن متغیر نیز Hoisted می‌شود، اما برخلاف `var`، مقداردهی اولیه (initialize) آن انجام نمی‌شود و تا قبل از تعریف آن قابل دسترسی نیستند. این وضعیت به نام "منطقه مرده زمانی" (Temporal Dead Zone) شناخته می‌شود (فاصله زمانی بین تعریف متغیر و مقداردهی آن). بنابراین، اگر سعی کنیم قبل از تعریف متغیر، به آن‌ دسترسی پیدا کنیم، جاوااسکریپت یک خطای `ReferenceError` ایجاد می‌کند. در نتیجه در خط `console.log(age)`، جاوااسکریپت یک خطای `ReferenceError` پرتاب می‌کند.

<blockquote dir="ltr" align="left">
Within the function, we first declare the `name` variable with the `var` keyword. This means that the variable gets hoisted (memory space is set up during the creation phase) with the default value of `undefined`, until we actually get to the line where we define the variable. We haven't defined the variable yet on the line where we try to log the `name` variable, so it still holds the value of `undefined`.

Variables with the `let` keyword (and `const`) are hoisted, but unlike `var`, don't get <i>initialized</i>. They are not accessible before the line we declare (initialize) them. This is called the "temporal dead zone". When we try to access the variables before they are declared, JavaScript throws a `ReferenceError`.
</blockquote>

</p>
</details>

---

###### 2. خروجی این کد چیست؟

```javascript
for (var i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 1);
}

for (let i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 1);
}
```

- الف: `0 1 2` و `0 1 2`
- ب: `0 1 2` و `3 3 3`
- ج: `3 3 3` و `0 1 2`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

برای پاسخ به این سوال ابتدا باید بدانیم که:

- متغیرهایی که با کلمه کلیدی `var` تعریف می‌شوند، می‌توانند به صورت global scope یا function scope باشند؛ اما متغیرهایی که با کلمه کلیدی `let` و `const` تعریف می‌شوند، علاوه بر global scope دارای محدوده‌ی block scope یعنی `{}` نیز هستند.
- تابع بازگشتی مربوط به `setTimeout` یک تابع غیرهمزمان (`async`) است، به دلیل وجود صفِ رویداد یا همان event queue، ولی حلقه‌ها به صورت پیش‌فرض `sync` یا همزمان هستند؛ بنابراین تابع بازگشتی مربوط به `setTimeout` بعد از اجرای کامل حلقه فراخوانی می‌شود.

**با این توضیح:**

1. **در حلقه اول (با `var`):**

از آنجایی که متغیر `i` در این حلقه با استفاده از کلمه کلیدی `var` تعریف شده، محدوده (scope) آن به صورت global (سراسری) در نظر گرفته می‌شود، در نتیجه به صورت مشترک برای کل حلقه استفاده می‌شود (در طول اجرای حلقه، مقدار `i` در هر بار تکرار یک واحد افزایش می‌یابد). در اینجا:

- تابع `setTimeout`، یک تابع غیر همزمان  (async) است و در زمان اجرای حلقه بلافاصله اجرا نمی‌شود.
- تا زمانی که `setTimeout` اجرا شود (پس از پایان حلقه)، مقدار `i` به عدد `3` رسیده است.
- بنابراین هر بار که `console.log(i)` اجرا می‌شود، مقدار نهایی `i` (یعنی `3`) چاپ می‌شود.

2. **در حلقه دوم (با `let`):**

متغیر `i` با کلمه کلیدی `let` تعریف شده است و گفتیم که متغیرهای تعریف‌شده با `let` به صورت block scope هستند، به این معنی که در هر تکرار، متغیر `i` یک مقدار جدیدی و مستقلی خواهد داشت و هر مقدار، تنها در محدوده (scope) همان حلقه معتبر است. در اینجا:

- هر `setTimeout`، مقدار فعلی `i` را ثبت می‌کند.
- بنابراین، مقادیر `0، 1 و 2` به ترتیب چاپ می‌شوند.

<blockquote dir="ltr" align="left">
Because of the event queue in JavaScript, the `setTimeout` callback function is called _after_ the loop has been executed. Since the variable `i` in the first loop was declared using the `var` keyword, this value was global. During the loop, we incremented the value of `i` by `1` each time, using the unary operator `++`. By the time the `setTimeout` callback function was invoked, `i` was equal to `3` in the first example.

In the second loop, the variable `i` was declared using the `let` keyword: variables declared with the `let` (and `const`) keyword are block-scoped (a block is anything between `{ }`). During each iteration, `i` will have a new value, and each value is scoped inside the loop.
</blockquote>

</p>
</details>

---

###### 3. خروجی این کد چیست؟

```javascript
const shape = {
  radius: 10,
  diameter() {
    return this.radius * 2;
  },
  perimeter: () => 2 * Math.PI * this.radius,
};

console.log(shape.diameter());
console.log(shape.perimeter());
```

- الف: `20` و `62.83185307179586`
- ب: `20` و `NaN`
- ج: `20` و `63`
- د: `NaN` و `63`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

برای پاسخ به این سوال ابتدا باید بدانیم که:

1. در توابع معمولی (regular function)، به صورت پیش‌فرض کلمه کلیدی `this` به Context یا زمینه‌ای اشاره دارد که تابع از آنجا فراخوانی می‌شود (بدون در نظر گرفته محل تعریف تابع). بنابراین محل تعریف تابع تأثیری بر مقدار `this` ندارد؛ آنچه مهم است، نحوه‌ی فراخوانی تابع است.

- اگر تابع به عنوان یک متد از یک آبجکت فراخوانی شود، `this` به آن آبجکت اشاره خواهد کرد.
- اگر تابع به صورت مستقل فراخوانی شود، `this` به Global Object (مثلاً `window` در مرورگر) یا در حالت `strict mode` به `undefined` اشاره می‌کند.
- در صورت استفاده از متدهای `call`، `apply` یا `bind` مقدار `this` به صورت صریح مشخص خواهد شد که به چه چیزی اشاره دارد.

2. در Arrow Function ها، مقدار `this` به Context یا زمینه‌ای که تابع در آن تعریف شده است، بستگی دارد (بدون در نظر گرفتن نحوه فراخوانی تابع). یعنی `this` را از محیط خارج از محلی که تابع در آن تعریف شده به ارث می‌برد و دیگر تحت تأثیر نحوه‌ی فراخوانی آن قرار نمی‌گیرد.

**با این توضیح:**

در متد `diameter`: یک تابع معمولی (regular function) است. در توابع معمولی، کلمه کلیدی `this` به آبجکت فراخوانی‌کننده (در اینجا -`shape`) اشاره می‌کند.

بنابراین:
- عبارت `this.radius` مقدار `10` را برمی‌گرداند.
- مقدار نهایی `10 * 2` برابر با `20` می‌باشد.

در متد `perimeter`: یک Arrow Function است. در توابع Arrow، کلمه کلیدی `this` به محیط خارج از محلی که تابع در آن تعریف شده، اشاره می‌کند و نه به آبجکت فراخوانی‌کننده.

- در اینجا، `this` به محیط خارج از `shape` اشاره می‌کند (مانند `window` در مرورگر یا `global` در Node.js).
- در این محیط، مقدار `radius` تعریف نشده است، بنابراین `this.radius` مقدار `undefined` را برمی‌گرداند.
- وقتی این مقدار (`undefined`) در `2 * Math.PI` ضرب می‌شود، نتیجه `NaN` خواهد شد.

<blockquote dir="ltr" align="left">
Note that the value of `diameter` is a regular function, whereas the value of `perimeter` is an arrow function.

With arrow functions, the `this` keyword refers to its current surrounding scope, unlike regular functions! This means that when we call `perimeter`, it doesn't refer to the shape object, but to its surrounding scope (window for example).

Since there is no value `radius` in the scope of the arrow function, `this.radius` returns `undefined` which, when multiplied by `2 * Math.PI`, results in `NaN`.
</blockquote>
</p>
</details>

---

###### 4. خروجی این کد چیست؟

```javascript
+true;
!'Lydia';
```

- الف: `1` و `false`
- ب: `false` و `NaN`
- ج: `false` و `false`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

**عملگر `+` برای `true`**:

- عملگر `+` یک عملگر یکتا (Unary Operator) است که سعی می‌کند عملوند خود را به **عدد** تبدیل کند.
- مقدار `true` در جاوااسکریپت معادل `1` و مقدار `false` برابر با `0` است.
- بنابراین `+true` مقدار `1` را برمی‌گرداند.

**عملگر `!` برای `'Lydia'`**:

- عبارت `'Lydia'` یک مقدار truthy است (یعنی مقداری که در شرایط منطقی به عنوان `true` در نظر گرفته می‌شود)، زیرا هر رشته غیر خالی در جاوااسکریپت truthy محسوب می‌شود.
- عملگر `!` مقدار منطقی عملوند را **برعکس** می‌کند.
  - در ابتدا، `'Lydia'` به `true` تبدیل می‌شود.
  - سپس، `!true` به `false` تبدیل می‌شود.

<blockquote dir="ltr" align="left">
The unary plus tries to convert an operand to a number. `true` is `1`, and `false` is `0`.

The string `'Lydia'` is a truthy value. What we're actually asking, is "Is this truthy value falsy؟". This returns `false`.
</blockquote>
</p>
</details>

---

###### 5. کدام یک درست است؟

```javascript
const bird = {
  size: 'small',
};

const mouse = {
  name: 'Mickey',
  small: true,
};
```

- الف: `mouse.bird.size` اشتباه است
- ب: `mouse[bird.size]` اشتباه است
- ج: `mouse[bird["size"]]` اشتباه است
- د: همه گزینه‌ها صحیح هستند

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

در جاوااسکریپت، تمام key های آبجکت، رشته (string) هستند (مگر اینکه از نوع Symbol باشند). حتی اگر آنها را به صورت رشته _تایپ_ نکنیم، جاوااسکریپت در پشت صحنه همیشه آن‌ها را به صورت خودکار به رشته تبدیل می‌کند.

جاوااسکریپت دستورات را تحلیل و تفسیر می‌کند. وقتی از علامت براکت `[]` استفاده می‌کنیم، جاوااسکریپت ابتدا اولین براکت باز `[` را می‌بیند و تا زمانی که براکت بسته `]` را پیدا نکند، به خواندن ادامه می‌دهد. سپس، عبارت داخل براکت را ارزیابی می‌کند.

**دسترسی به `mouse.bird.size`**:

- وقتی از نقطه‌گذاری (dot notation) استفاده می‌کنیم (مانند `mouse.bird.size`)، جاوااسکریپت به دنبال کلید `bird` در آبجکت `mouse` می‌گردد.
- از آنجا که آبجکت `mouse` پراپرتی‌ای به نام `bird` ندارد، مقدار `mouse.bird` برابر با `undefined` می‌شود.
- سپس، تلاش برای دسترسی به `size` روی یک مقدار `undefined` باعث ایجاد خطا می‌شود: `Cannot read property 'size' of undefined`. (در واقع داریم از جاوااسکریپت می‌پرسیم که مقدار `undefined.size` چیست)

**دسترسی به `mouse[bird.size]`**:

- در اینجا از براکت‌گذاری (bracket notation) استفاده شده است. ابتدا جاوااسکریپت مقدار `bird.size` را ارزیابی می‌کند که برابر با `'small'` است.
- سپس، جاوااسکریپت به دنبال کلید `'small'` در آبجکت `mouse` می‌گردد.
- چون کلید `small` در `mouse` وجود دارد و مقدار آن `true` است، این معتبر است.

**دسترسی به `mouse[bird["size"]]`**:

- مشابه مورد قبلی است. ابتدا `bird["size"]` ارزیابی شده و مقدار `'small'` به دست می‌آید.
- سپس، جاوااسکریپت به دنبال کلید `'small'` در شیء `mouse` می‌گردد.
- این نیز معتبر است و مقدار `true` را برمی‌گرداند.


<blockquote dir="ltr" align="left">
In JavaScript, all object keys are strings (unless it's a Symbol). Even though we might not _type_ them as strings, they are always converted into strings under the hood.

JavaScript interprets (or unboxes) statements. When we use bracket notation, it sees the first opening bracket `[` and keeps going until it finds the closing bracket `]`. Only then, it will evaluate the statement.

`mouse[bird.size]`: First it evaluates `bird.size`, which is `"small"`. `mouse["small"]` returns `true`

However, with dot notation, this doesn't happen. `mouse` does not have a key called `bird`, which means that `mouse.bird` is `undefined`. Then, we ask for the `size` using dot notation: `mouse.bird.size`. Since `mouse.bird` is `undefined`, we're actually asking `undefined.size`. This isn't valid, and will throw an error similar to `Cannot read property "size" of undefined`.
</blockquote>
</p>
</details>

---

###### 6. خروجی این کد چیست؟

```javascript
let c = { greeting: 'Hey!' };
let d;

d = c;
c.greeting = 'Hello';
console.log(d.greeting);
```

- الف: `Hello`
- ب: `Hey!`
- ج: `undefined`
- د: `ReferenceError`
- هـ: `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

برای پاسخ به این سوال ابتدا باید بدانیم که:

- در جاوااسکریپت، نحوه‌ی ارسال داده‌ها به متغیرها یا توابع به دو روش **Pass by Value** و **Pass by Reference** انجام می‌شود. این دو روش به نوع داده‌ای (data type) که ارسال می‌شود بستگی دارند.
- در جاوااسکریپت، **آبجکت‌ها** با ارجاع (by reference) تعامل دارند. یعنی هر آبجکت به یک مرجع (آدرس حافظه) یا reference در حافظه اشاره می‌کند.
- وقتی یک آبجکت را به یک متغیر اختصاص می‌دهیم، در واقع آن متغیر یک ارجاع (reference) از آن آبجکت را در حافظه دریافت می‌کند، نه یک کپی از مقدار آن. درنتیجه، هر تغییری که روی آن آبجکت اعمال شود، منجر به تغییر مقدار آن مرجع در حافظه خواهد شد.

**با این توضیح:**

در اینجا، متغیر `c` یک آبجکت را نگه می‌دارد که شامل کلیدی به نام `greeting` با مقدار `'Hey!'` است.

وقتی مقدار `d` را برابر با `c` تعیین می‌کنیم یعنی `d = c`:

- هر دو متغیر `c` و `d` به آدرس همان آبجکت در حافظه اشاره می‌کنند.

<img src="https://i.imgur.com/ko5k0fs.png" width="200">

سپس، مقدار `c.greeting` به `'Hello'` تغییر داده می‌شود:

- چون هر دو متغیر به یک آبجکت در حافظه اشاره می‌کنند، تغییر در یکی از آن‌ها منجر به تغییر در دیگری خواهد شد.

در نهایت، `console.log(d.greeting)` مقدار `Hello` را چاپ می‌کند.

<blockquote dir="ltr" align="left">
In JavaScript, all objects interact by _reference_ when setting them equal to each other.

First, variable `c` holds a value to an object. Later, we assign `d` with the same reference that `c` has to the object.

<img src="https://i.imgur.com/ko5k0fs.png" width="200">

When you change one object, you change all of them.
</blockquote>
</p>
</details>

---

###### 7. خروجی این کد چیست؟

```javascript
let a = 3;
let b = new Number(3);
let c = 3;

console.log(a == b);
console.log(a === b);
console.log(b === c);
```

- الف: `true` `false` `true`
- ب: `false` `false` `true`
- ج: `true` `false` `false`
- د: `false` `true` `true`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

تابع سازنده `new Number()` یک تابع داخلی (built-in function constructor) است. اگرچه شبیه یک عدد به نظر می‌رسد، اما در واقع یک عدد نیست؛ بلکه یک آبجکت است که ویژگی‌های اضافی زیادی دارد.

وقتی از عملگر `==` (عملگر برابری) استفاده می‌کنیم، فقط بررسی می‌کند که آیا _مقدارشان (value)_ باهم برابر است یا نه. در اینجا، مقدار هر دو متغیر `3` است. بنابراین، نتیجه `true` خواهد بود.

اما وقتی از عملگر `===` (عملگر برابری سختگیرانه) استفاده می‌کنیم، هم مقدار (value) _و_ هم نوع (type) باید یکسان باشند. که در اینجا این‌گونه نیست: خروجی نوع `new Number()` یک عدد نیست، بلکه یک **آبجکت** است. بنابراین هر دو، نتیجه‌ی `false` را خواهد گرداند.

**به عبارت دیگر:**

در مورد `a == b`:

- عملگر **برابری ساده (`==`)** فقط مقادیر (value) را مقایسه می‌کند و تفاوتی بین انواع داده‌ها (type) قائل نمی‌شود.
- متغیر `a` یک مقدار عددی است و `b` یک آبجکت (از نوع `Number`) است.
- جاوااسکریپت به صورت خودکار، مقدار `b` را به مقدار عددی آن تبدیل می‌کند، که برابر با `3` است.
- بنابراین، `3 == 3` نتیجه `true` می‌دهد.

در مورد `a === b` و `b === c`:

- عملگر **برابری سختگیرانه (`===`)** هم مقدار (value) و هم نوع (type) را مقایسه می‌کند.
- متغیر `a` و `c` یک مقدار عددی (number) است، اما `b` یک آبجکت (از نوع `Number`) است.
- بنابراین، نتیجه مقایسه `a === b` یا `b === c` برابر با `false` خواهد بود.

<blockquote dir="ltr" align="left">
`new Number()` is a built-in function constructor. Although it looks like a number, it's not really a number: it has a bunch of extra features and is an object.

When we use the `==` operator (Equality operator), it only checks whether it has the same _value_. They both have the value of `3`, so it returns `true`.

However, when we use the `===` operator (Strict equality operator), both value _and_ type should be the same. It's not: `new Number()` is not a number, it's an **object**. Both return `false.`
</blockquote>
</p>
</details>

---

###### 8. خروجی این کد چیست؟

```javascript
class Chameleon {
  static colorChange(newColor) {
    this.newColor = newColor;
    return this.newColor;
  }

  constructor({ newColor = 'green' } = {}) {
    this.newColor = newColor;
  }
}

const freddie = new Chameleon({ newColor: 'purple' });
console.log(freddie.colorChange('orange'));
```

- الف: `orange`
- ب: `purple`
- ج: `green`
- د: `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

تابع `colorChange` یک متد استاتیک (static) است. در جاوااسکریپت، متدهای استاتیک به گونه‌ای طراحی شده‌اند که فقط در سازنده‌ی (constructor) همان کلاسی که ایجاد/تعریف شده‌اند، وجود دارند (قابل دسترسی هستند) و نمی‌توان آن‌ها را به فرزند آن کلاس انتقال داد یا از طریق نمونه‌های آن کلاس (class instance) فراخوانی کرد. از آنجایی که `freddie` یک نمونه (instance) از کلاس `Chameleon` است، این تابع نمی‌تواند روی آن فراخوانی شود. در نتیجه، یک خطای `TypeError` ایجاد می‌شود.

<blockquote dir="ltr" align="left">
The `colorChange` funcgtion is static. Static methods are designed to live only on the constructor in which they are created, and cannot be passed down to any children or called upon class instances. Since `freddie` is an instance of class Chameleon, the function cannot be called upon it. A `TypeError` is thrown.
</blockquote>
</p>
</details>

---

###### 9. خروجی این کد چیست؟

```javascript
let greeting;
greetign = {}; // اشتباه تایپی (Typo)!
console.log(greetign);
```

- الف: `{}`
- ب: `ReferenceError: greetign is not defined`
- ج: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

در اینجا، متغیر `greetign` به اشتباه تایپ شده و تعریف نشده است. با این حال، جاوااسکریپت (وقتی `"use strict"` استفاده نشده باشد)، این متغیر را به طور خودکار به شیء سراسری (global object) اضافه می‌کند.

1. در مرورگرها، این مقدار (یعنی `{}`) به `window.greetign`، `frames.greetign` و `self.greetign` اضافه می‌شود.
2. در Node.js، به `global.greetign` اضافه می‌شود.
3. در web workers به `self.greetign` اضافه می‌شود.
4. در تمام محیط‌ها (environments) به `globalThis.greetign` اضافه می‌شود.

بنابراین، وقتی مقدار `{}` به `greetign` نسبت داده می‌شود، به عنوان یک شیء خالی در محیط سراسری ذخیره می‌شود.

برای جلوگیری از این اتفاق، می‌توانیم از `"use strict"` استفاده کنیم. این حالت تضمین می‌کند که قبل از مقداردهی/انتساب به یک متغیر، حتماً آن را تعریف کرده باشیم (در صورت عدم تعریف، خطای `ReferenceError` دریافت خواهیم کرد).

<blockquote dir="ltr" align="left">
It logs the object, because we just created an empty object on the global object! When we mistyped `greeting` as `greetign`, the JS interpreter actually saw this as:

1. `global.greetign = {}` in Node.js
2. `window.greetign = {}`, `frames.greetign = {}` and `self.greetign` in browsers.
3. `self.greetign` in web workers.
4. `globalThis.greetign` in all environments.

In order to avoid this, we can use `"use strict"`. This makes sure that you have declared a variable before setting it equal to anything.
</blockquote>
</p>
</details>

---

###### 10. وقتی این کار را انجام می‌دهیم، چه اتفاقی می‌افتد؟

```javascript
function bark() {
  console.log('Woof!');
}

bark.animal = 'dog';
```

- الف: هیچ مشکلی ندارد، این کاملاً درست است!
- ب: خطای `SyntaxError` می‌دهد، زیرا با این روش نمی‌توانیم ویژگی‌هایی به یک تابع اضافه کنیم.
- ج: مقدار `"Woof"` لاگ می‌شود.
- د: خطای `ReferenceError` می‌دهد.

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

در جاوااسکریپت این ممکن است، زیرا توابع از نوع آبجکت هستند! (هر چیزی به جز انواع داده اولیه یا primitive type، آبجکت محسوب می‌شود.)

تابع یک نوع خاص از آبجکت است. کدی که شما به عنوان یک تابع می‌نویسید، در واقع خود تابع نیست. تابع در جاوااسکریپت یک آبجکت با ویژگی‌هایی (properties) است که یکی از این ویژگی‌ها، قابلیت اجرا شدن (invocable بودن) است.

بنابراین، می‌توانیم به توابع، ویژگی‌های دلخواهی اضافه کنیم، همانطور که به یک آبجکت می‌توانستیم.

در این مثال، ما یک ویژگی به نام `animal` را با مقدار `'dog'` به تابع `bark` اضافه کرده‌ایم که کاملاً مجاز و بدون خطاست.

<blockquote dir="ltr" align="left">
This is possible in JavaScript, because functions are objects! (Everything besides primitive types are objects)

A function is a special type of object. The code you write yourself isn't the actual function. The function is an object with properties. This property is invocable.
</blockquote>
</p>
</details>

---

###### 11. خروجی این کد چیست؟

```javascript
function Person(firstName, lastName) {
  this.firstName = firstName;
  this.lastName = lastName;
}

const member = new Person('Lydia', 'Hallie');
Person.getFullName = function () {
  return `${this.firstName} ${this.lastName}`;
};

console.log(member.getFullName());
```

- الف: `TypeError`
- ب: `SyntaxError`
- ج: `Lydia Hallie`
- د: `undefined` `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

در جاوااسکریپت، توابع آبجکت هستند و می‌توان به آن‌ها ویژگی‌هایی را اضافه کرد.

در اینجا، متد `getFullName` به تابع سازنده `Person` اضافه شده است، اما این متد فقط به خود تابع سازنده (constructor function) تعلق دارد و به نمونه‌های ایجاد شده توسط آن (مانند `member`) دسترسی ندارد.

مقدار `member` یک نمونه از کلاس `Person` است. با این حال، `getFullName` به نمونه‌های این کلاس اضافه نشده است؛ بلکه به تابع سازنده (constructor function) یعنی `Person` تعلق دارد.

وقتی تلاش می‌کنید `member.getFullName()` را فراخوانی کنید، جاوااسکریپت خطای `TypeError` می‌دهد، زیرا متد `getFullName` در نمونه (instance) آن وجود ندارد.

اگر می‌خواهید یک متد، برای تمام نمونه‌های آن شیء، در دسترس باشد، باید آن ویژگی را به `prototype` تابع سازنده اضافه کنید، به عنوان مثال:

<div dir="ltr" align="left">

```js
Person.prototype.getFullName = function () {
  return `${this.firstName} ${this.lastName}`;
};
```

</div>


<blockquote dir="ltr" align="left">
In JavaScript, functions are objects, and therefore, the method `getFullName` gets added to the constructor function object itself. For that reason, we can call `Person.getFullName()`, but `member.getFullName` throws a `TypeError`.

If you want a method to be available to all object instances, you have to add it to the prototype property:

```js
Person.prototype.getFullName = function () {
  return `${this.firstName} ${this.lastName}`;
};
```
</blockquote>
</p>
</details>

---

###### 12. خروجی این کد چیست؟

```javascript
function Person(firstName, lastName) {
  this.firstName = firstName;
  this.lastName = lastName;
}

const lydia = new Person('Lydia', 'Hallie');
const sarah = Person('Sarah', 'Smith');

console.log(lydia);
console.log(sarah);
```

- الف: `Person {firstName: "Lydia", lastName: "Hallie"}` و `undefined`
- ب: `Person {firstName: "Lydia", lastName: "Hallie"}` و `Person {firstName: "Sarah", lastName: "Smith"}`
- ج: `Person {firstName: "Lydia", lastName: "Hallie"}` و `{}`
- د: `Person {firstName: "Lydia", lastName: "Hallie"}` و `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

1. **هنگام استفاده از کلمه کلیدی `new` برای ایجاد یک آبجکت:**

وقتی از `new` برای فراخوانی یک تابع سازنده استفاده می‌کنیم، جاوااسکریپت یک آبجکت جدید ایجاد می‌کند که مقدار `this` به آن آبجکت ساخته شده، اشاره می‌کند.

بنابراین، وقتی `const lydia = new Person('Lydia', 'Hallie')` اجرا می‌شود:

- جاوااسکریپت یک آبجکت جدید از نوع Person ایجاد می‌کند.
- مقدار `this.firstName` برابر `'Lydia'` و مقدار `this.lastName` برابر `'Hallie'` تعیین خواهد شد.
- در نتیجه خروجی متغیر `lydia` برابر با `Person {firstName: "Lydia", lastName: "Hallie"}` خواهد بود.

<br />

2. **فراخوانی تابع بدون استفاده از کلمه کلیدی `new`:**

وقتی تابع `Person('Sarah', 'Smith')` را _بدون_ `new` فراخوانی می‌کنیم:

- مقدار `this` به آبجکت سراسری یا global object اشاره می‌کند. (به عنوان مثال در مرورگر به `window` و در Node.js به `global`)
- در نتیجه، مقادیر `firstName` و `lastName` به متغیرهای سراسری تبدیل می‌شوند، یعنی:

<div dir="ltr" align="left">

```js
window.firstName = 'Sarah'; // یا global.firstName = 'Sarah'
window.lastName = 'Smith'; // یا global.lastName = 'Smith'
```

</div>

- با توجه به اینکه تابع `Person` هیچ مقداری به عنوان خروجی برنمی‌گرداند، بنابراین متغیر `sarah` مقدار `undefined` را خواهد داشت.

<blockquote dir="ltr" align="left">
For `sarah`, we didn't use the `new` keyword. When using `new`, `this` refers to the new empty object we create. However, if you don't add `new`, `this` refers to the **global object**!

We said that `this.firstName` equals `"Sarah"` and `this.lastName` equals `"Smith"`. What we actually did, is defining `global.firstName = 'Sarah'` and `global.lastName = 'Smith'`. `sarah` itself is left `undefined`, since we don't return a value from the `Person` function.
</blockquote>
</p>
</details>

---

###### 13. سه مرحله‌‌ی انتشار رویداد (event propagation) چیست؟ (ترتبب گزینه‌ها از چپ به راست می‌باشد)

- الف: Target > Capturing > Bubbling
- ب: Bubbling > Target > Capturing
- ج: Target > Bubbling > Capturing
- د: Capturing > Target > Bubbling

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

در جاوااسکریپت، زمانی که یک رویداد (Event) مانند کلیک رخ می‌دهد، فرآیند انتشار رویداد (event propagation) در سه مرحله انجام می‌شود:

1. **مرحله Capturing Phase**: در این مرحله، رویداد از بالاترین عنصر والد (مانند `document` یا `window`) شروع می‌شود و به سمت عنصر هدف (Target) حرکت می‌کند.
2. **مرحله Target Phase**: در این مرحله، رویداد به عنصر هدف (Target) می‌رسد و اجرا می‌شود. این همان جایی است که رویداد در خودِ عنصری که کلیک یا عمل دیگری روی آن انجام شده، اجرا می‌شود.
3. **مرحله Bubbling Phase**: پس از اجرا در عنصر هدف (Target)، رویداد به سمت عناصر والد بازمی‌گردد.

به عبارت دیگر، در مرحله کپچرینگ (Capturing)، رویداد از عناصر والد به سمت عنصر هدف (Target) حرکت می‌کند. پس از رسیدن به عنصر هدف، مرحله بالا رفتن (Bubbling) آغاز می‌شود و رویداد از عنصر هدف به سمت عناصر والد بازمی‌گردد.

<img src="https://i.imgur.com/N18oRgd.png" width="200">

**توجه داشته باشید** که پرسش در مورد **ترتیب مراحل انتشار رویداد** بود، نه _مقدار پیش‌فرض_ آرگومان `useCapture` در متد `addEventListener` در جاوااسکریپت، ترتیب مراحل انتشار همیشه مطابق با گزینه `د` می‌باشد.

<blockquote dir="ltr" align="left">
During the **capturing** phase, the event goes through the ancestor elements down to the target element. It then reaches the **target** element, and **bubbling** begins.

<br />

<img src="https://i.imgur.com/N18oRgd.png" width="200">

</blockquote>
</p>
</details>

---

###### 14. آیا همه اشیا در جاوااسکریپت دارای پروتوتایپ (Prototype) هستند؟

- الف: بله
- ب: خیر

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

در جاوااسکریپت، پروتوتایپ (Prototype) یک مکانیزم ارث‌بری است که به اشیا اجازه می‌دهد ویژگی‌ها و متدها را از سایر اشیا به ارث ببرند. هر شیء در جاوااسکریپت (به جز شیء پایه) به یک شیء دیگر متصل است که به آن پروتوتایپ می‌گویند.

همه‌ی آبجکت‌ها در جاوااسکریپت یک پروتوتایپ (`prototype`) دارند، به جز آبجکت پایه (base object).

آبجکت پایه (base object)، آبجکتی است که توسط کاربر ایجاد شده یا با استفاده از کلمه کلیدی `new` ساخته شده است. این آبجکت به برخی از متدها و پراپرتی‌ها داخلی (built-in) جاوااسکریپت مانند `toString` دسترسی دارد. به همین دلیل است که می‌توانید از متدهای داخلی (built-in) جاوااسکریپت استفاده کنیم!

تمام این متدهای داخلی روی پروتوتایپ قرار دارند. اگر جاوااسکریپت نتواند مستقیماً متدی را روی آبجکت شما پیدا کند، از زنجیره پروتوتایپ (prototype chain) آن را جستجو می‌کند، که باعث می‌شود این متدها برای شما قابل دسترسی شوند.


<blockquote dir="ltr" align="left">
All objects have prototypes, except for the **base object**. The base object is the object created by the user, or an object that is created using the `new` keyword. The base object has access to some methods and properties, such as `.toString`. This is the reason why you can use built-in JavaScript methods! All of such methods are available on the prototype. Although JavaScript can't find it directly on your object, it goes down the prototype chain and finds it there, which makes it accessible for you.
</blockquote>
</p>
</details>

---

###### 15. خروجی این کد چیست؟

```javascript
function sum(a, b) {
  return a + b;
}

sum(1, '2');
```

- الف: `NaN`
- ب: `TypeError`
- ج: `"12"`
- د: `3`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

جاوااسکریپت یک زبان با **تایپ پویا** است؛ این بدان معنی است که لازم نیست نوع متغیرها را از قبل مشخص کنیم. مقادیر می‌توانند به‌طور خودکار به نوع دیگری تبدیل شوند بدون اینکه متوجه شویم، که به این فرآیند "تبدیل نوع ضمنی" (_Implicit Type Coercion_) گفته می‌شود. **Coercion** به معنای تبدیل یک نوع داده به نوع دیگر است.

در این مثال، جاوااسکریپت هنگام جمع یک مقدار عددی (`1`) و یک رشته (`'2'`)، عدد را به رشته تبدیل می‌کند تا بتواند عمل جمع (که در اینجا در واقع الحاق است) را انجام دهد. همان‌طور که می‌توانیم رشته‌ها را به هم متصل کنیم (مثل `"Hello" + "World"`)، در این مورد هم اتفاقی مشابه می‌افتد: در نتیجه `1` (عددی) به `"1"` (رشته) تبدیل شده و جمع دو رشته‌ی `"1" + "2"` برابر با `"12"` می‌شود.


<blockquote dir="ltr" align="left">
JavaScript is a **dynamically typed language**: we don't specify what types certain variables are. Values can automatically be converted into another type without you knowing, which is called _implicit type coercion_. **Coercion** is converting from one type into another.

In this example, JavaScript converts the number `1` into a string, in order for the function to make sense and return a value. During the addition of a numeric type (`1`) and a string type (`'2'`), the number is treated as a string. We can concatenate strings like `"Hello" + "World"`, so what's happening here is `"1" + "2"` which returns `"12"`.
</blockquote>
</p>
</details>

---

###### 16. خروجی این کد چیست؟

```javascript
let number = 0;
console.log(number++);
console.log(++number);
console.log(number);
```

- الف: `1` `1` `2`
- ب: `1` `2` `2`
- ج: `0` `2` `2`
- د: `0` `1` `2`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

عملگر یکانی **پسوندی (postfix)** `++`:

عملگر `++` وقتی پسوندی استفاده شود (<code dir="ltr">number++</code>)، ابتدا مقدار متغیر را برمی‌گرداند، سپس آن را یک واحد افزایش می‌دهد. در اولین `console.log(number++)` مقدار `0` چاپ می‌شود، اما پس از آن `number` به `1` افزایش می‌یابد. بنابراین در این حالت:

1. مقدار فعلی متغیر را بازمی‌گرداند (در اینجا مقدار `0` را برمی‌گرداند).
2. سپس مقدار متغیر را افزایش می‌دهد (حالا مقدار `number` برابر با `1` می‌شود).

عملگر یکانی **پیشوندی (prefix)** `++`:

وقتی پیشوندی استفاده شود (<code dir="ltr">++number</code>)، ابتدا مقدار افزایش می‌یابد، سپس مقدار جدید برگردانده می‌شود. در `console.log(++number)` مقدار `number` که اکنون `1` است ابتدا به `2` تبدیل می‌شود و `2` چاپ می‌شود. بنابراین در این حالت:

1. ابتدا مقدار متغیر را افزایش می‌دهد (مقدار `number` برابر با `2` می‌شود).
2. سپس مقدار جدید متغیر را بازمی‌گرداند (در اینجا مقدار `2` را برمی‌گرداند).

در نتیجه، خروجی کد `0 2 2` خواهد بود.


<blockquote dir="ltr" align="left">
The **postfix** unary operator `++`:

1. Returns the value (this returns `0`)
2. Increments the value (number is now `1`)

The **prefix** unary operator `++`:

1. Increments the value (number is now `2`)
2. Returns the value (this returns `2`)

This returns `0 2 2`.
</blockquote>
</p>
</details>

---

###### 17. خروجی این کد چیست؟

```javascript
function getPersonInfo(one, two, three) {
  console.log(one);
  console.log(two);
  console.log(three);
}

const person = 'Lydia';
const age = 21;

getPersonInfo`${person} is ${age} years old`;
```

- الف: <span dir="ltr">`"Lydia"` `21` `["", " is ", " years old"]`</span>
- ب: <span dir="ltr">`["", " is ", " years old"]` `"Lydia"` `21`</span>
- ج: <span dir="ltr">`"Lydia"` `["", " is ", " years old"]` `21`</span>

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

در این کد از **tagged template literals** استفاده شده است. وقتی از یک تابع به عنوان tagged template literal استفاده می‌شود، جاوااسکریپت به صورت زیر عمل می‌کند:

1. **قسمت‌های ثابت (Strings)**: اولین آرگومان ارسال شده به تابع یک **آرایه** حاوی قسمت‌های ثابت رشته است. این قسمت‌ها، بخش‌هایی از رشته هستند که در بین مقادیر جایگزین‌ شده (یعنی <code dir="ltr">${}</code>) قرار دارند.
2. **مقادیر جایگزین‌شده (Substitutions)**: آرگومان‌های بعدی (دو و سه و چهار و …) مقادیری هستند که در جایگزین‌های <code dir="ltr">${}</code> قرار می‌گیرند (که در اینجا `person` و `age` می‌باشند.).

در این مثال:

- بخش ثابت رشته‌ها: <code dir="ltr">["", " is ", " years old"]</code>
- مقادیر جایگزین شده: `"Lydia"` و `21`

بنابراین، هنگام فراخوانی <code dir="ltr">getPersonInfo\`${person} is ${age} years old\`</code>، پارامترها به ترتیب زیر خواهند بود:

1. پارامتر اول: <code dir="ltr">["", " is ", " years old"]</code>
2. پارامتر دوم: `"Lydia"`
3. پارامتر سوم: `21`

و در خروجی نیز موارد زیر به ترتیب چاپ خواهند شد:

<pre dir="ltr">
["", " is ", " years old"]
"Lydia"
21
</pre>

در نتیجه گزینه `ب` صحیح می‌باشد.


<blockquote dir="ltr" align="left">
If you use tagged template literals, the value of the first argument is always an array of the string values. The remaining arguments get the values of the passed expressions!
</blockquote>
</p>
</details>

---

###### 18. خروجی این کد چیست؟

```javascript
function checkAge(data) {
  if (data === { age: 18 }) {
    console.log('You are an adult!');
  } else if (data == { age: 18 }) {
    console.log('You are still an adult.');
  } else {
    console.log(`Hmm.. You don't have an age I guess`);
  }
}

checkAge({ age: 18 });
```

- الف: <code dir="ltr">You are an adult!</code>
- ب: <code dir="ltr">You are still an adult.</code>
- ج: <code dir="ltr">Hmm.. You don't have an age I guess</code>

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

- آبجکت‌ها در جاوااسکریپت به عنوان یک _رفرنس_ در حافظه ذخیره می‌شوند (در واقع آن متغیر یک _reference_ از آن آبجکت را در حافظه دریافت می‌کند، نه یک کپی از مقدار آن).
- زمانی که یک آبجکت را با یک متغیر (آبجکت) دیگر مقایسه می‌کنیم، در واقع، جاوااسکریپت بررسی می‌کند که آیا هر دو متغیر به **همان محل حافظه** اشاره می‌کنند یا خیر، نه اینکه مقادیر داخلی آنها یکسان باشد. در نتیجه مقایسه آبجکت‌ها چه به صورت `===` و چه به صورت `==` انجام شود، با توجه به اینکه رفرنس هر کدام در حافظه متفاوت است، نتیجه همیشه `false` خواهد بود. (برخلاف مقادیر primitive که مقایسه آن‌ها بر اساس **مقدار یا value** آن انجام می‌شود)

با توجه به این توضیح، گزینه `ج` صحیح می‌باشد.

<blockquote dir="ltr" align="left">
When testing equality, primitives are compared by their _value_, while objects are compared by their _reference_. JavaScript checks if the objects have a reference to the same location in memory.

The two objects that we are comparing don't have that: the object we passed as a parameter refers to a different location in memory than the object we used in order to check equality.

This is why both `{ age: 18 } === { age: 18 }` and `{ age: 18 } == { age: 18 }` return `false`.
</blockquote>
</p>
</details>

---

###### 19. خروجی این کد چیست؟

```javascript
function getAge(...args) {
  console.log(typeof args);
}

getAge(21);
```

- الف: `"number"`
- ب: `"array"`
- ج: `"object"`
- د: `"NaN"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

- در این کد از **Rest Parameters** استفاده شده است. پارامترهای rest به ما اجازه می‌دهند تا تعداد نامحدودی از آرگومان‌ها را به عنوان یک **آرایه** از یک تابع دریافت کنیم.
- تابع <code dir="ltr">getAge(21)</code> تنها با یک آرگومان (`21`) فراخوانی شده است، بنابراین `args` برابر با `[21]` می‌باشد.
- از آنجا که آرایه‌ها در جاوااسکریپت یک نوع آبجکت می‌باشند، در نتیجه خروجی مقدار `typeof args` برابر با `"object"` خواهد بود.

با توجه به این توضیح، گزینه `ج` صحیح می‌باشد.

<blockquote dir="ltr" align="left">
The rest parameter (`...args`) lets us "collect" all remaining arguments into an array. An array is an object, so `typeof args` returns `"object"`
</blockquote>
</p>
</details>

---

###### 20. خروجی این کد چیست؟

```javascript
function getAge() {
  'use strict';
  age = 21;
  console.log(age);
}

getAge();
```

- الف: `21`
- ب: `undefined`
- ج: `ReferenceError`
- د: `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

در بدنه‌ی تابع `getAge` ، از حالت سخت‌گیرانه (`"use strict"`) استفاده شده است. وقتی از این عبارت استفاده می‌کنیم، باعث می‌شود که جاوااسکریپت قوانین بیشتری را برای نوشتن کد اعمال کند تا اشتباهات رایج را شناسایی و از بروز از خطاهای احتمالی جلوگیری کند. به عبارت دیگر، در این حالت، قوانین و محدودیت‌هایی به زبان اعمال می‌شود که به طور پیش‌فرض در حالت معمولی وجود ندارند. یکی از این محدودیت‌ها در خصوص مقدار دهی به یک متغیر، بدون تعریف آن می‌باشد.

در تابع `getAge`، سعی شده که به متغیر `age` مقداردهی شود، بدون اینکه قبلاً آن را با کلمه کلیدی `var`, `let` یا `const` تعریف کرده باشد.

در حالت **غیر سخت‌گیرانه**، این کار باعث می‌شود که متغیر `age` به یک متغیر سراسری (global) تبدیل شود و منجر به بروز هیچگونه خطایی نخواهد شد. اما در حالت **سخت‌گیرانه**، گفتیم که اختصاص مقدار به یک متغیر تعریف نشده قابل قبول نیست، در نتیجه منجر به `throw` شدن خطای `ReferenceError` می‌شود، زیرا متغیر `age` قبلاً تعریف نشده است.

بنابراین، اجرای این کد باعث ایجاد خطای `ReferenceError` می‌شود و گزینه `ج` صحیح می‌باشد.


<blockquote dir="ltr" align="left">
With `"use strict"`, you can make sure that you don't accidentally declare global variables. We never declared the variable `age`, and since we use `"use strict"`, it will throw a reference error. If we didn't use `"use strict"`, it would have worked, since the property `age` would have gotten added to the global object.
</blockquote>
</p>
</details>

---

###### 21. مقدار `num` چیست؟

```javascript
const sum = eval('10*10+5');
```

- الف: `105`
- ب: `"105"`
- ج: `TypeError`
- د: `"10*10+5"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

`eval` evaluates code that's passed as a string. If it's an expression, like in this case, it evaluates the expression. The expression is `10 * 10 + 5`. This returns the number `105`.

</p>
</details>

---

###### 22. How long is cool_secret accessible؟

```javascript
sessionStorage.setItem('cool_secret', 123);
```

- الف: Forever, the data doesn't get lost.
- ب: When the user closes the tab.
- ج: When the user closes the entire browser, not only the tab.
- د: When the user shuts off their computer.

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

The data stored in `sessionStorage` is removed after closing the _tab_.

If you used `localStorage`, the data would've been there forever, unless for example `localStorage.clear()` is invoked.

</p>
</details>

---

###### 23. خروجی این کد چیست؟

```javascript
var num = 8;
var num = 10;

console.log(num);
```

- الف: `8`
- ب: `10`
- ج: `SyntaxError`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the `var` keyword, you can declare multiple variables with the same name. The variable will then hold the latest value.

You cannot do this with `let` or `const` since they're block-scoped and therefore can't be redeclared.

</p>
</details>

---

###### 24. خروجی این کد چیست؟

```javascript
const obj = { 1: 'a', 2: 'b', 3: 'c' };
const set = new Set([1, 2, 3, 4, 5]);

obj.hasOwnProperty('1');
obj.hasOwnProperty(1);
set.has('1');
set.has(1);
```

- الف: `false` `true` `false` `true`
- ب: `false` `true` `true` `true`
- ج: `true` `true` `false` `true`
- د: `true` `true` `true` `true`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

All object keys (excluding Symbols) are strings under the hood, even if you don't type it yourself as a string. This is why `obj.hasOwnProperty('1')` also returns true.

It doesn't work that way for a set. There is no `'1'` in our set: `set.has('1')` returns `false`. It has the numeric type `1`, `set.has(1)` returns `true`.

</p>
</details>

---

###### 25. خروجی این کد چیست؟

```javascript
const obj = { a: 'one', b: 'two', a: 'three' };
console.log(obj);
```

- الف: `{ a: "one", b: "two" }`
- ب: `{ b: "two", a: "three" }`
- ج: `{ a: "three", b: "two" }`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

If you have two keys with the same name, the key will be replaced. It will still be in its first position, but with the last specified value.

</p>
</details>

---

###### 26. The JavaScript global execution context creates two things for you: the global object, and the "this" keyword.

- الف: true
- ب: false
- ج: it depends

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The base execution context is the global execution context: it's what's accessible everywhere in your code.

</p>
</details>

---

###### 27. خروجی این کد چیست؟

```javascript
for (let i = 1; i < 5; i++) {
  if (i === 3) continue;
  console.log(i);
}
```

- الف: `1` `2`
- ب: `1` `2` `3`
- ج: `1` `2` `4`
- د: `1` `3` `4`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `continue` statement skips an iteration if a certain condition returns `true`.

</p>
</details>

---

###### 28. خروجی این کد چیست؟

```javascript
String.prototype.giveLydiaPizza = () => {
  return 'Just give Lydia pizza already!';
};

const name = 'Lydia';

console.log(name.giveLydiaPizza());
```

- الف: `"Just give Lydia pizza already!"`
- ب: `TypeError: not a function`
- ج: `SyntaxError`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

`String` is a built-in constructor, that we can add properties to. I just added a method to its prototype. Primitive strings are automatically converted into a string object, generated by the string prototype function. So, all strings (string objects) have access to that method!

</p>
</details>

---

###### 29. خروجی این کد چیست؟

```javascript
const a = {};
const b = { key: 'b' };
const c = { key: 'c' };

a[b] = 123;
a[c] = 456;

console.log(a[b]);
```

- الف: `123`
- ب: `456`
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

Object keys are automatically converted into strings. We are trying to set an object as a key to object `a`, with the value of `123`.

However, when we stringify an object, it becomes `"[object Object]"`. So what we are saying here, is that `a["[object Object]"] = 123`. Then, we can try to do the same again. `c` is another object that we are implicitly stringifying. So then, `a["[object Object]"] = 456`.

Then, we log `a[b]`, which is actually `a["[object Object]"]`. We just set that to `456`, so it returns `456`.

</p>
</details>

---

###### 30. خروجی این کد چیست؟

```javascript
const foo = () => console.log('First');
const bar = () => setTimeout(() => console.log('Second'));
const baz = () => console.log('Third');

bar();
foo();
baz();
```

- الف: `First` `Second` `Third`
- ب: `First` `Third` `Second`
- ج: `Second` `First` `Third`
- د: `Second` `Third` `First`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

We have a `setTimeout` function and invoked it first. Yet, it was logged last.

This is because in browsers, we don't just have the runtime engine, we also have something called a `WebAPI`. The `WebAPI` gives us the `setTimeout` function to start with, and for example the DOM.

After the _callback_ is pushed to the WebAPI, the `setTimeout` function itself (but not the callback!) is popped off the stack.

<img src="https://i.imgur.com/X5wsHOg.png" width="200">

Now, `foo` gets invoked, and `"First"` is being logged.

<img src="https://i.imgur.com/Pvc0dGq.png" width="200">

`foo` is popped off the stack, and `baz` gets invoked. `"Third"` gets logged.

<img src="https://i.imgur.com/WhA2bCP.png" width="200">

The WebAPI can't just add stuff to the stack whenever it's ready. Instead, it pushes the callback function to something called the _queue_.

<img src="https://i.imgur.com/NSnDZmU.png" width="200">

This is where an event loop starts to work. An **event loop** looks at the stack and task queue. If the stack is empty, it takes the first thing on the queue and pushes it onto the stack.

<img src="https://i.imgur.com/uyiScAI.png" width="200">

`bar` gets invoked, `"Second"` gets logged, and it's popped off the stack.

</p>
</details>

---

###### 31. هنگام کلیک روی `button`، مقدار `event.target` چیست؟

```html
<div onclick="console.log('first div')">
  <div onclick="console.log('second div')">
    <button onclick="console.log('button')">Click!</button>
  </div>
</div>
```

- الف: Outer `div`
- ب: Inner `div`
- ج: `button`
- د: An array of all nested elements.

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The deepest nested element that caused the event is the target of the event. You can stop bubbling by `event.stopPropagation`

</p>
</details>

---

###### 32. وقتی روی پاراگراف کلیک می‌کنید، چه خروجی‌ای در لاگ ثبت می‌شود؟

```html
<div onclick="console.log('div')">
  <p onclick="console.log('p')">Click here!</p>
</div>
```

- الف: `p` `div`
- ب: `div` `p`
- ج: `p`
- د: `div`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

If we click `p`, we see two logs: `p` and `div`. During event propagation, there are 3 phases: capturing, targeting, and bubbling. By default, event handlers are executed in the bubbling phase (unless you set `useCapture` to `true`). It goes from the deepest nested element outwards.

</p>
</details>

---

###### 33. خروجی این کد چیست؟

```javascript
const person = { name: 'Lydia' };

function sayHi(age) {
  return `${this.name} is ${age}`;
}

console.log(sayHi.call(person, 21));
console.log(sayHi.bind(person, 21));
```

- الف: `undefined is 21` `Lydia is 21`
- ب: `function` `function`
- ج: `Lydia is 21` `Lydia is 21`
- د: `Lydia is 21` `function`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

With both, we can pass the object to which we want the `this` keyword to refer to. However, `.call` is also _executed immediately_!

`.bind.` returns a _copy_ of the function, but with a bound context! It is not executed immediately.

</p>
</details>

---

###### 34. خروجی این کد چیست؟

```javascript
function sayHi() {
  return (() => 0)();
}

console.log(typeof sayHi());
```

- الف: `"object"`
- ب: `"number"`
- ج: `"function"`
- د: `"undefined"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

The `sayHi` function returns the returned value of the immediately invoked function expression (IIFE). This function returned `0`, which is type `"number"`.

FYI: `typeof` can return the following list of values: `undefined`, `boolean`, `number`, `bigint`, `string`, `symbol`, `function` and `object`. Note that `typeof null` returns `"object"`.

</p>
</details>

---

###### 35. کدام‌یک از این مقادیر falsy هستند؟

```javascript
0;
new Number(0);
('');
(' ');
new Boolean(false);
undefined;
```

- الف: `0`, `''`, `undefined`
- ب: `0`, `new Number(0)`, `''`, `new Boolean(false)`, `undefined`
- ج: `0`, `''`, `new Boolean(false)`, `undefined`
- د: All of them are falsy

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

There are 8 falsy values:

- `undefined`
- `null`
- `NaN`
- `false`
- `''` (empty string)
- `0`
- `-0`
- `0n` (BigInt(0))

Function constructors, like `new Number` and `new Boolean` are truthy.

</p>
</details>

---

###### 36. خروجی این کد چیست؟

```javascript
console.log(typeof typeof 1);
```

- الف: `"number"`
- ب: `"string"`
- ج: `"object"`
- د: `"undefined"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

`typeof 1` returns `"number"`.
`typeof "number"` returns `"string"`

</p>
</details>

---

###### 37. خروجی این کد چیست؟

```javascript
const numbers = [1, 2, 3];
numbers[10] = 11;
console.log(numbers);
```

- الف: `[1, 2, 3, null x 7, 11]`
- ب: `[1, 2, 3, 11]`
- ج: `[1, 2, 3, empty x 7, 11]`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

When you set a value to an element in an array that exceeds the length of the array, JavaScript creates something called "empty slots". These actually have the value of `undefined`, but you will see something like:

`[1, 2, 3, empty x 7, 11]`

depending on where you run it (it's different for every browser, node, etc.)

</p>
</details>

---

###### 38. خروجی این کد چیست؟

```javascript
(() => {
  let x, y;
  try {
    throw new Error();
  } catch (x) {
    (x = 1), (y = 2);
    console.log(x);
  }
  console.log(x);
  console.log(y);
})();
```

- الف: `1` `undefined` `2`
- ب: `undefined` `undefined` `undefined`
- ج: `1` `1` `2`
- د: `1` `undefined` `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The `catch` block receives the argument `x`. This is not the same `x` as the variable when we pass arguments. This variable `x` is block-scoped.

Later, we set this block-scoped variable equal to `1`, and set the value of the variable `y`. Now, we log the block-scoped variable `x`, which is equal to `1`.

Outside of the `catch` block, `x` is still `undefined`, and `y` is `2`. When we want to `console.log(x)` outside of the `catch` block, it returns `undefined`, and `y` returns `2`.

</p>
</details>

---

###### 39. Everything in JavaScript is either a...

- الف: primitive or object
- ب: function or object
- ج: trick question! only objects
- د: number or object

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

JavaScript only has primitive types and objects.

Primitive types are `boolean`, `null`, `undefined`, `bigint`, `number`, `string`, and `symbol`.

What differentiates a primitive from an object is that primitives do not have any properties or methods; however, you'll note that `'foo'.toUpperCase()` evaluates to `'FOO'` and does not result in a `TypeError`. This is because when you try to access a property or method on a primitive like a string, JavaScript will implicitly wrap the primitive type using one of the wrapper classes, i.e. `String`, and then immediately discard the wrapper after the expression evaluates. All primitives except for `null` and `undefined` exhibit this behavior.

</p>
</details>

---

###### 40. خروجی این کد چیست؟

```javascript
[
  [0, 1],
  [2, 3],
].reduce(
  (acc, cur) => {
    return acc.concat(cur);
  },
  [1, 2]
);
```

- الف: `[0, 1, 2, 3, 1, 2]`
- ب: `[6, 1, 2]`
- ج: `[1, 2, 0, 1, 2, 3]`
- د: `[1, 2, 6]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

`[1, 2]` is our initial value. This is the value we start with, and the value of the very first `acc`. During the first round, `acc` is `[1,2]`, and `cur` is `[0, 1]`. We concatenate them, which results in `[1, 2, 0, 1]`.

Then, `[1, 2, 0, 1]` is `acc` and `[2, 3]` is `cur`. We concatenate them, and get `[1, 2, 0, 1, 2, 3]`

</p>
</details>

---

###### 41. خروجی این کد چیست؟

```javascript
!!null;
!!'';
!!1;
```

- الف: `false` `true` `false`
- ب: `false` `false` `true`
- ج: `false` `true` `true`
- د: `true` `true` `false`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

`null` is falsy. `!null` returns `true`. `!true` returns `false`.

`""` is falsy. `!""` returns `true`. `!true` returns `false`.

`1` is truthy. `!1` returns `false`. `!false` returns `true`.

</p>
</details>

---

###### 42. متد `setInterval` در مرورگر چه مقداری را برمی‌گرداند؟

```javascript
setInterval(() => console.log('Hi'), 1000);
```

- الف: a unique id
- ب: the amount of milliseconds specified
- ج: the passed function
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

It returns a unique id. This id can be used to clear that interval with the `clearInterval()` function.

</p>
</details>

---

###### 43. این چه مقداری را برمی‌گرداند؟

```javascript
[...'Lydia'];
```

- الف: `["L", "y", "d", "i", "a"]`
- ب: `["Lydia"]`
- ج: `[[], "Lydia"]`
- د: `[["L", "y", "d", "i", "a"]]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

A string is an iterable. The spread operator maps every character of an iterable to one element.

</p>
</details>

---

###### 44. خروجی این کد چیست؟

```javascript
function* generator(i) {
  yield i;
  yield i * 2;
}

const gen = generator(10);

console.log(gen.next().value);
console.log(gen.next().value);
```

- الف: `[0, 10], [10, 20]`
- ب: `20, 20`
- ج: `10, 20`
- د: `0, 10 and 10, 20`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Regular functions cannot be stopped mid-way after invocation. However, a generator function can be "stopped" midway, and later continue from where it stopped. Every time a generator function encounters a `yield` keyword, the function yields the value specified after it. Note that the generator function in that case doesn’t _return_ the value, it _yields_ the value.

First, we initialize the generator function with `i` equal to `10`. We invoke the generator function using the `next()` method. The first time we invoke the generator function, `i` is equal to `10`. It encounters the first `yield` keyword: it yields the value of `i`. The generator is now "paused", and `10` gets logged.

Then, we invoke the function again with the `next()` method. It starts to continue where it stopped previously, still with `i` equal to `10`. Now, it encounters the next `yield` keyword, and yields `i * 2`. `i` is equal to `10`, so it returns `10 * 2`, which is `20`. This results in `10, 20`.

</p>
</details>

---

###### 45. این چه مقداری را برمی‌گرداند؟

```javascript
const firstPromise = new Promise((res, rej) => {
  setTimeout(res, 500, 'one');
});

const secondPromise = new Promise((res, rej) => {
  setTimeout(res, 100, 'two');
});

Promise.race([firstPromise, secondPromise]).then((res) => console.log(res));
```

- الف: `"one"`
- ب: `"two"`
- ج: `"two" "one"`
- د: `"one" "two"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

When we pass multiple promises to the `Promise.race` method, it resolves/rejects the _first_ promise that resolves/rejects. To the `setTimeout` method, we pass a timer: 500ms for the first promise (`firstPromise`), and 100ms for the second promise (`secondPromise`). This means that the `secondPromise` resolves first with the value of `'two'`. `res` now holds the value of `'two'`, which gets logged.

</p>
</details>

---

###### 46. خروجی این کد چیست؟

```javascript
let person = { name: 'Lydia' };
const members = [person];
person = null;

console.log(members);
```

- الف: `null`
- ب: `[null]`
- ج: `[{}]`
- د: `[{ name: "Lydia" }]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

First, we declare a variable `person` with the value of an object that has a `name` property.

<img src="https://i.imgur.com/TML1MbS.png" width="200">

Then, we declare a variable called `members`. We set the first element of that array equal to the value of the `person` variable. Objects interact by _reference_ when setting them equal to each other. When you assign a reference from one variable to another, you make a _copy_ of that reference. (note that they don't have the _same_ reference!)

<img src="https://i.imgur.com/FSG5K3F.png" width="300">

Then, we set the variable `person` equal to `null`.

<img src="https://i.imgur.com/sYjcsMT.png" width="300">

We are only modifying the value of the `person` variable, and not the first element in the array, since that element has a different (copied) reference to the object. The first element in `members` still holds its reference to the original object. When we log the `members` array, the first element still holds the value of the object, which gets logged.

</p>
</details>

---

###### 47. خروجی این کد چیست؟

```javascript
const person = {
  name: 'Lydia',
  age: 21,
};

for (const item in person) {
  console.log(item);
}
```

- الف: `{ name: "Lydia" }, { age: 21 }`
- ب: `"name", "age"`
- ج: `"Lydia", 21`
- د: `["name", "Lydia"], ["age", 21]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With a `for-in` loop, we can iterate through object keys, in this case `name` and `age`. Under the hood, object keys are strings (if they're not a Symbol). On every loop, we set the value of `item` equal to the current key it’s iterating over. First, `item` is equal to `name`, and gets logged. Then, `item` is equal to `age`, which gets logged.

</p>
</details>

---

###### 48. خروجی این کد چیست؟

```javascript
console.log(3 + 4 + '5');
```

- الف: `"345"`
- ب: `"75"`
- ج: `12`
- د: `"12"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

Operator associativity is the order in which the compiler evaluates the expressions, either left-to-right or right-to-left. This only happens if all operators have the _same_ precedence. We only have one type of operator: `+`. For addition, the associativity is left-to-right.

`3 + 4` gets evaluated first. This results in the number `7`.

`7 + '5'` results in `"75"` because of coercion. JavaScript converts the number `7` into a string, see question 15. We can concatenate two strings using the `+`operator. `"7" + "5"` results in `"75"`.

</p>
</details>

---

###### 49. مقدار `num` چیست؟

```javascript
const num = parseInt('7*6', 10);
```

- الف: `42`
- ب: `"42"`
- ج: `7`
- د: `NaN`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Only the first number in the string is returned. Based on the _radix_ (the second argument in order to specify what type of number we want to parse it to: base 10, hexadecimal, octal, binary, etc.), the `parseInt` checks whether the characters in the string are valid. Once it encounters a character that isn't a valid number in the radix, it stops parsing and ignores the following characters.

`*` is not a valid number. It only parses `"7"` into the decimal `7`. `num` now holds the value of `7`.

</p>
</details>

---

###### 50. خروجی این کد چیست؟

```javascript
[1, 2, 3].map((num) => {
  if (typeof num === 'number') return;
  return num * 2;
});
```

- الف: `[]`
- ب: `[null, null, null]`
- ج: `[undefined, undefined, undefined]`
- د: `[ 3 x empty ]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

When mapping over the array, the value of `num` is equal to the element it’s currently looping over. In this case, the elements are numbers, so the condition of the if statement `typeof num === "number"` returns `true`. The map function creates a new array and inserts the values returned from the function.

However, we don’t return a value. When we don’t return a value from the function, the function returns `undefined`. For every element in the array, the function block gets called, so for each element we return `undefined`.

</p>
</details>

---

###### 51. خروجی این کد چیست؟

```javascript
function getInfo(member, year) {
  member.name = 'Lydia';
  year = '1998';
}

const person = { name: 'Sarah' };
const birthYear = '1997';

getInfo(person, birthYear);

console.log(person, birthYear);
```

- الف: `{ name: "Lydia" }, "1997"`
- ب: `{ name: "Sarah" }, "1998"`
- ج: `{ name: "Lydia" }, "1998"`
- د: `{ name: "Sarah" }, "1997"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

Arguments are passed by _value_, unless their value is an object, then they're passed by _reference_. `birthYear` is passed by value, since it's a string, not an object. When we pass arguments by value, a _copy_ of that value is created (see question 46).

The variable `birthYear` has a reference to the value `"1997"`. The argument `year` also has a reference to the value `"1997"`, but it's not the same value as `birthYear` has a reference to. When we update the value of `year` by setting `year` equal to `"1998"`, we are only updating the value of `year`. `birthYear` is still equal to `"1997"`.

The value of `person` is an object. The argument `member` has a (copied) reference to the _same_ object. When we modify a property of the object `member` has a reference to, the value of `person` will also be modified, since they both have a reference to the same object. `person`'s `name` property is now equal to the value `"Lydia"`

</p>
</details>

---

###### 52. خروجی این کد چیست؟

```javascript
function greeting() {
  throw 'Hello world!';
}

function sayHi() {
  try {
    const data = greeting();
    console.log('It worked!', data);
  } catch (e) {
    console.log('Oh no an error:', e);
  }
}

sayHi();
```

- الف: `It worked! Hello world!`
- ب: `Oh no an error: undefined`
- ج: `SyntaxError: can only throw Error objects`
- د: `Oh no an error: Hello world!`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

With the `throw` statement, we can create custom errors. With this statement, you can throw exceptions. An exception can be a <b>string</b>, a <b>number</b>, a <b>boolean</b> or an <b>object</b>. In this case, our exception is the string `'Hello world!'`.

With the `catch` statement, we can specify what to do if an exception is thrown in the `try` block. An exception is thrown: the string `'Hello world!'`. `e` is now equal to that string, which we log. This results in `'Oh an error: Hello world!'`.

</p>
</details>

---

###### 53. خروجی این کد چیست؟

```javascript
function Car() {
  this.make = 'Lamborghini';
  return { make: 'Maserati' };
}

const myCar = new Car();
console.log(myCar.make);
```

- الف: `"Lamborghini"`
- ب: `"Maserati"`
- ج: `ReferenceError`
- د: `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

When a constructor function is called with the `new` keyword, it creates an object and sets the `this` keyword to refer to that object. By default, if the constructor function doesn't explicitly return anything, it will return the newly created object.

In this case, the constructor function `Car` explicitly returns a new object with `make` set to `"Maserati"`, which overrides the default behavior. Therefore, when `new Car()` is called, the _returned_ object is assigned to `myCar`, resulting in the output being `"Maserati"` when `myCar.make` is accessed.

</p>
</details>

---

###### 54. خروجی این کد چیست؟

```javascript
(() => {
  let x = (y = 10);
})();

console.log(typeof x);
console.log(typeof y);
```

- الف: `"undefined", "number"`
- ب: `"number", "number"`
- ج: `"object", "number"`
- د: `"number", "undefined"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

`let x = (y = 10);` is actually shorthand for:

```javascript
y = 10;
let x = y;
```

When we set `y` equal to `10`, we actually add a property `y` to the global object (`window` in the browser, `global` in Node). In a browser, `window.y` is now equal to `10`.

Then, we declare a variable `x` with the value of `y`, which is `10`. Variables declared with the `let` keyword are _block scoped_, they are only defined within the block they're declared in; the immediately invoked function expression (IIFE) in this case. When we use the `typeof` operator, the operand `x` is not defined: we are trying to access `x` outside of the block it's declared in. This means that `x` is not defined. Values who haven't been assigned a value or declared are of type `"undefined"`. `console.log(typeof x)` returns `"undefined"`.

However, we created a global variable `y` when setting `y` equal to `10`. This value is accessible anywhere in our code. `y` is defined, and holds a value of type `"number"`. `console.log(typeof y)` returns `"number"`.

</p>
</details>

---

###### 55. خروجی این کد چیست؟

```javascript
class Dog {
  constructor(name) {
    this.name = name;
  }
}

Dog.prototype.bark = function () {
  console.log(`Woof I am ${this.name}`);
};

const pet = new Dog('Mara');

pet.bark();

delete Dog.prototype.bark;

pet.bark();
```

- الف: `"Woof I am Mara"`, `TypeError`
- ب: `"Woof I am Mara"`, `"Woof I am Mara"`
- ج: `"Woof I am Mara"`, `undefined`
- د: `TypeError`, `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

We can delete properties from objects using the `delete` keyword, also on the prototype. By deleting a property on the prototype, it is not available anymore in the prototype chain. In this case, the `bark` function is not available anymore on the prototype after `delete Dog.prototype.bark`, yet we still try to access it.

When we try to invoke something that is not a function, a `TypeError` is thrown. In this case `TypeError: pet.bark is not a function`, since `pet.bark` is `undefined`.

</p>
</details>

---

###### 56. خروجی این کد چیست؟

```javascript
const set = new Set([1, 1, 2, 3, 4]);

console.log(set);
```

- الف: `[1, 1, 2, 3, 4]`
- ب: `[1, 2, 3, 4]`
- ج: `{1, 1, 2, 3, 4}`
- د: `{1, 2, 3, 4}`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The `Set` object is a collection of _unique_ values: a value can only occur once in a set.

We passed the iterable `[1, 1, 2, 3, 4]` with a duplicate value `1`. Since we cannot have two of the same values in a set, one of them is removed. This results in `{1, 2, 3, 4}`.

</p>
</details>

---

###### 57. خروجی این کد چیست؟

```javascript
// counter.js
let counter = 10;
export default counter;
```

```javascript
// index.js
import myCounter from './counter';

myCounter += 1;

console.log(myCounter);
```

- الف: `10`
- ب: `11`
- ج: `Error`
- د: `NaN`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

An imported module is _read-only_: you cannot modify the imported module. Only the module that exports them can change its value.

When we try to increment the value of `myCounter`, it throws an error: `myCounter` is read-only and cannot be modified.

</p>
</details>

---

###### 58. خروجی این کد چیست؟

```javascript
const name = 'Lydia';
age = 21;

console.log(delete name);
console.log(delete age);
```

- الف: `false`, `true`
- ب: `"Lydia"`, `21`
- ج: `true`, `true`
- د: `undefined`, `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The `delete` operator returns a boolean value: `true` on a successful deletion, else it'll return `false`. However, variables declared with the `var`, `const`, or `let` keywords cannot be deleted using the `delete` operator.

The `name` variable was declared with a `const` keyword, so its deletion is not successful: `false` is returned. When we set `age` equal to `21`, we actually added a property called `age` to the global object. You can successfully delete properties from objects this way, also the global object, so `delete age` returns `true`.

</p>
</details>

---

###### 59. خروجی این کد چیست؟

```javascript
const numbers = [1, 2, 3, 4, 5];
const [y] = numbers;

console.log(y);
```

- الف: `[[1, 2, 3, 4, 5]]`
- ب: `[1, 2, 3, 4, 5]`
- ج: `1`
- د: `[1]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

We can unpack values from arrays or properties from objects through destructuring. For example:

```javascript
[a, b] = [1, 2];
```

<img src="https://i.imgur.com/ADFpVop.png" width="200">

The value of `a` is now `1`, and the value of `b` is now `2`. What we actually did in the question, is:

```javascript
[y] = [1, 2, 3, 4, 5];
```

<img src="https://i.imgur.com/NzGkMNk.png" width="200">

This means that the value of `y` is equal to the first value in the array, which is the number `1`. When we log `y`, `1` is returned.

</p>
</details>

---

###### 60. خروجی این کد چیست؟

```javascript
const user = { name: 'Lydia', age: 21 };
const admin = { admin: true, ...user };

console.log(admin);
```

- الف: `{ admin: true, user: { name: "Lydia", age: 21 } }`
- ب: `{ admin: true, name: "Lydia", age: 21 }`
- ج: `{ admin: true, user: ["Lydia", 21] }`
- د: `{ admin: true }`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

It's possible to combine objects using the spread operator `...`. It lets you create copies of the key/value pairs of one object, and add them to another object. In this case, we create copies of the `user` object, and add them to the `admin` object. The `admin` object now contains the copied key/value pairs, which results in `{ admin: true, name: "Lydia", age: 21 }`.

</p>
</details>

---

###### 61. خروجی این کد چیست؟

```javascript
const person = { name: 'Lydia' };

Object.defineProperty(person, 'age', { value: 21 });

console.log(person);
console.log(Object.keys(person));
```

- الف: `{ name: "Lydia", age: 21 }`, `["name", "age"]`
- ب: `{ name: "Lydia", age: 21 }`, `["name"]`
- ج: `{ name: "Lydia"}`, `["name", "age"]`
- د: `{ name: "Lydia"}`, `["age"]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the `defineProperty` method, we can add new properties to an object, or modify existing ones. When we add a property to an object using the `defineProperty` method, they are by default _not enumerable_. The `Object.keys` method returns all _enumerable_ property names from an object, in this case only `"name"`.

Properties added using the `defineProperty` method are immutable by default. You can override this behavior using the `writable`, `configurable` and `enumerable` properties. This way, the `defineProperty` method gives you a lot more control over the properties you're adding to an object.

</p>
</details>

---

###### 62. خروجی این کد چیست؟

```javascript
const settings = {
  username: 'lydiahallie',
  level: 19,
  health: 90,
};

const data = JSON.stringify(settings, ['level', 'health']);
console.log(data);
```

- الف: `"{"level":19, "health":90}"`
- ب: `"{"username": "lydiahallie"}"`
- ج: `"["level", "health"]"`
- د: `"{"username": "lydiahallie", "level":19, "health":90}"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The second argument of `JSON.stringify` is the _replacer_. The replacer can either be a function or an array, and lets you control what and how the values should be stringified.

If the replacer is an _array_, only the property names included in the array will be added to the JSON string. In this case, only the properties with the names `"level"` and `"health"` are included, `"username"` is excluded. `data` is now equal to `"{"level":19, "health":90}"`.

If the replacer is a _function_, this function gets called on every property in the object you're stringifying. The value returned from this function will be the value of the property when it's added to the JSON string. If the value is `undefined`, this property is excluded from the JSON string.

</p>
</details>

---

###### 63. خروجی این کد چیست؟

```javascript
let num = 10;

const increaseNumber = () => num++;
const increasePassedNumber = (number) => number++;

const num1 = increaseNumber();
const num2 = increasePassedNumber(num1);

console.log(num1);
console.log(num2);
```

- الف: `10`, `10`
- ب: `10`, `11`
- ج: `11`, `11`
- د: `11`, `12`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The unary operator `++` _first returns_ the value of the operand, _then increments_ the value of the operand. The value of `num1` is `10`, since the `increaseNumber` function first returns the value of `num`, which is `10`, and only increments the value of `num` afterward.

`num2` is `10`, since we passed `num1` to the `increasePassedNumber`. `number` is equal to `10`(the value of `num1`). Again, the unary operator `++` _first returns_ the value of the operand, _then increments_ the value of the operand. The value of `number` is `10`, so `num2` is equal to `10`.

</p>
</details>

---

###### 64. خروجی این کد چیست؟

```javascript
const value = { number: 10 };

const multiply = (x = { ...value }) => {
  console.log((x.number *= 2));
};

multiply();
multiply();
multiply(value);
multiply(value);
```

- الف: `20`, `40`, `80`, `160`
- ب: `20`, `40`, `20`, `40`
- ج: `20`, `20`, `20`, `40`
- د: `NaN`, `NaN`, `20`, `40`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

In ES6, we can initialize parameters with a default value. The value of the parameter will be the default value, if no other value has been passed to the function, or if the value of the parameter is `"undefined"`. In this case, we spread the properties of the `value` object into a new object, so `x` has the default value of `{ number: 10 }`.

The default argument is evaluated at _call time_! Every time we call the function, a _new_ object is created. We invoke the `multiply` function the first two times without passing a value: `x` has the default value of `{ number: 10 }`. We then log the multiplied value of that number, which is `20`.

The third time we invoke multiply, we do pass an argument: the object called `value`. The `*=` operator is actually shorthand for `x.number = x.number * 2`: we modify the value of `x.number`, and log the multiplied value `20`.

The fourth time, we pass the `value` object again. `x.number` was previously modified to `20`, so `x.number *= 2` logs `40`.

</p>
</details>

---

###### 65. خروجی این کد چیست؟

```javascript
[1, 2, 3, 4].reduce((x, y) => console.log(x, y));
```

- الف: `1` `2` and `3` `3` and `6` `4`
- ب: `1` `2` and `2` `3` and `3` `4`
- ج: `1` `undefined` and `2` `undefined` and `3` `undefined` and `4` `undefined`
- د: `1` `2` and `undefined` `3` and `undefined` `4`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The first argument that the `reduce` method receives is the _accumulator_, `x` in this case. The second argument is the _current value_, `y`. With the reduce method, we execute a callback function on every element in the array, which could ultimately result in one single value.

In this example, we are not returning any values, we are simply logging the values of the accumulator and the current value.

The value of the accumulator is equal to the previously returned value of the callback function. If you don't pass the optional `initialValue` argument to the `reduce` method, the accumulator is equal to the first element on the first call.

On the first call, the accumulator (`x`) is `1`, and the current value (`y`) is `2`. We don't return from the callback function, we log the accumulator, and the current values: `1` and `2` get logged.

If you don't return a value from a function, it returns `undefined`. On the next call, the accumulator is `undefined`, and the current value is `3`. `undefined` and `3` get logged.

On the fourth call, we again don't return from the callback function. The accumulator is again `undefined`, and the current value is `4`. `undefined` and `4` get logged.

</p>
</details>

---

###### 66. With which constructor can we successfully extend the `Dog` class؟

```javascript
class Dog {
  constructor(name) {
    this.name = name;
  }
};

class Labrador extends Dog {
  // 1
  constructor(name, size) {
    this.size = size;
  }
  // 2
  constructor(name, size) {
    super(name);
    this.size = size;
  }
  // 3
  constructor(size) {
    super(name);
    this.size = size;
  }
  // 4
  constructor(name, size) {
    this.name = name;
    this.size = size;
  }

};
```

- الف: 1
- ب: 2
- ج: 3
- د: 4

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

In a derived class, you cannot access the `this` keyword before calling `super`. If you try to do that, it will throw a ReferenceError: 1 and 4 would throw a reference error.

With the `super` keyword, we call that parent class's constructor with the given arguments. The parent's constructor receives the `name` argument, so we need to pass `name` to `super`.

The `Labrador` class receives two arguments, `name` since it extends `Dog`, and `size` as an extra property on the `Labrador` class. They both need to be passed to the constructor function on `Labrador`, which is done correctly using constructor 2.

</p>
</details>

---

###### 67. خروجی این کد چیست؟

```javascript
// index.js
console.log('running index.js');
import { sum } from './sum.js';
console.log(sum(1, 2));

// sum.js
console.log('running sum.js');
export const sum = (a, b) => a + b;
```

- الف: `running index.js`, `running sum.js`, `3`
- ب: `running sum.js`, `running index.js`, `3`
- ج: `running sum.js`, `3`, `running index.js`
- د: `running index.js`, `undefined`, `running sum.js`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the `import` keyword, all imported modules are _pre-parsed_. This means that the imported modules get run _first_, and the code in the file that imports the module gets executed _after_.

This is a difference between `require()` in CommonJS and `import`! With `require()`, you can load dependencies on demand while the code is being run. If we had used `require` instead of `import`, `running index.js`, `running sum.js`, `3` would have been logged to the console.

</p>
</details>

---

###### 68. خروجی این کد چیست؟

```javascript
console.log(Number(2) === Number(2));
console.log(Boolean(false) === Boolean(false));
console.log(Symbol('foo') === Symbol('foo'));
```

- الف: `true`, `true`, `false`
- ب: `false`, `true`, `false`
- ج: `true`, `false`, `true`
- د: `true`, `true`, `true`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

Every Symbol is entirely unique. The purpose of the argument passed to the Symbol is to give the Symbol a description. The value of the Symbol is not dependent on the passed argument. As we test equality, we are creating two entirely new symbols: the first `Symbol('foo')`, and the second `Symbol('foo')`. These two values are unique and not equal to each other, `Symbol('foo') === Symbol('foo')` returns `false`.

</p>
</details>

---

###### 69. خروجی این کد چیست؟

```javascript
const name = 'Lydia Hallie';
console.log(name.padStart(13));
console.log(name.padStart(2));
```

- الف: `"Lydia Hallie"`, `"Lydia Hallie"`
- ب: `" Lydia Hallie"`, `" Lydia Hallie"` (`"[13x whitespace]Lydia Hallie"`, `"[2x whitespace]Lydia Hallie"`)
- ج: `" Lydia Hallie"`, `"Lydia Hallie"` (`"[1x whitespace]Lydia Hallie"`, `"Lydia Hallie"`)
- د: `"Lydia Hallie"`, `"Lyd"`,

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With the `padStart` method, we can add padding to the beginning of a string. The value passed to this method is the _total_ length of the string together with the padding. The string `"Lydia Hallie"` has a length of `12`. `name.padStart(13)` inserts 1 space at the start of the string, because 12 + 1 is 13.

If the argument passed to the `padStart` method is smaller than the length of the array, no padding will be added.

</p>
</details>

---

###### 70. خروجی این کد چیست؟

```javascript
console.log('🥑' + '💻');
```

- الف: `"🥑💻"`
- ب: `257548`
- ج: A string containing their code points
- د: Error

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

With the `+` operator, you can concatenate strings. In this case, we are concatenating the string `"🥑"` with the string `"💻"`, resulting in `"🥑💻"`.

</p>
</details>

---

###### 71. How can we log the values that are commented out after the console.log statement؟

```javascript
function* startGame() {
  const answer = yield 'Do you love JavaScript؟';
  if (answer !== 'Yes') {
    return "Oh wow... Guess we're done here";
  }
  return 'JavaScript loves you back ❤️';
}

const game = startGame();
console.log(/* 1 */); // Do you love JavaScript؟
console.log(/* 2 */); // JavaScript loves you back ❤️
```

- الف: `game.next("Yes").value` and `game.next().value`
- ب: `game.next.value("Yes")` and `game.next.value()`
- ج: `game.next().value` and `game.next("Yes").value`
- د: `game.next.value()` and `game.next.value("Yes")`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

A generator function "pauses" its execution when it sees the `yield` keyword. First, we have to let the function yield the string "Do you love JavaScript؟", which can be done by calling `game.next().value`.

Every line is executed, until it finds the first `yield` keyword. There is a `yield` keyword on the first line within the function: the execution stops with the first yield! _This means that the variable `answer` is not defined yet!_

When we call `game.next("Yes").value`, the previous `yield` is replaced with the value of the parameters passed to the `next()` function, `"Yes"` in this case. The value of the variable `answer` is now equal to `"Yes"`. The condition of the if-statement returns `false`, and `JavaScript loves you back ❤️` gets logged.

</p>
</details>

---

###### 72. خروجی این کد چیست؟

```javascript
console.log(String.raw`Hello\nworld`);
```

- الف: `Hello world!`
- ب: `Hello` <br />&nbsp; &nbsp; &nbsp;`world`
- ج: `Hello\nworld`
- د: `Hello\n` <br /> &nbsp; &nbsp; &nbsp;`world`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

`String.raw` returns a string where the escapes (`\n`, `\v`, `\t` etc.) are ignored! Backslashes can be an issue since you could end up with something like:

`` const path = `C:\Documents\Projects\table.html` ``

Which would result in:

`"C:DocumentsProjects able.html"`

With `String.raw`, it would simply ignore the escape and print:

`C:\Documents\Projects\table.html`

In this case, the string is `Hello\nworld`, which gets logged.

</p>
</details>

---

###### 73. خروجی این کد چیست؟

```javascript
async function getData() {
  return await Promise.resolve('I made it!');
}

const data = getData();
console.log(data);
```

- الف: `"I made it!"`
- ب: `Promise {<resolved>: "I made it!"}`
- ج: `Promise {<pending>}`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

An async function always returns a promise. The `await` still has to wait for the promise to resolve: a pending promise gets returned when we call `getData()` in order to set `data` equal to it.

If we wanted to get access to the resolved value `"I made it"`, we could have used the `.then()` method on `data`:

`data.then(res => console.log(res))`

This would've logged `"I made it!"`

</p>
</details>

---

###### 74. خروجی این کد چیست؟

```javascript
function addToList(item, list) {
  return list.push(item);
}

const result = addToList('apple', ['banana']);
console.log(result);
```

- الف: `['apple', 'banana']`
- ب: `2`
- ج: `true`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

The `.push()` method returns the _length_ of the new array! Previously, the array contained one element (the string `"banana"`) and had a length of `1`. After adding the string `"apple"` to the array, the array contains two elements, and has a length of `2`. This gets returned from the `addToList` function.

The `push` method modifies the original array. If you wanted to return the _array_ from the function rather than the _length of the array_, you should have returned `list` after pushing `item` to it.

</p>
</details>

---

###### 75. خروجی این کد چیست؟

```javascript
const box = { x: 10, y: 20 };

Object.freeze(box);

const shape = box;
shape.x = 100;

console.log(shape);
```

- الف: `{ x: 100, y: 20 }`
- ب: `{ x: 10, y: 20 }`
- ج: `{ x: 100 }`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

`Object.freeze` makes it impossible to add, remove, or modify properties of an object (unless the property's value is another object).

When we create the variable `shape` and set it equal to the frozen object `box`, `shape` also refers to a frozen object. You can check whether an object is frozen by using `Object.isFrozen`. In this case, `Object.isFrozen(shape)` would return true, since the variable `shape` has a reference to a frozen object.

Since `shape` is frozen, and since the value of `x` is not an object, we cannot modify the property `x`. `x` is still equal to `10`, and `{ x: 10, y: 20 }` gets logged.

</p>
</details>

---

###### 76. خروجی این کد چیست؟

```javascript
const { firstName: myName } = { firstName: 'Lydia' };

console.log(firstName);
```

- الف: `"Lydia"`
- ب: `"myName"`
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

By using [destructuring assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) syntax we can unpack values from arrays, or properties from objects, into distinct variables:

```javascript
const { firstName } = { firstName: 'Lydia' };
// ES5 version:
// var firstName = { firstName: 'Lydia' }.firstName;

console.log(firstName); // "Lydia"
```

Also, a property can be unpacked from an object and assigned to a variable with a different name than the object property:

```javascript
const { firstName: myName } = { firstName: 'Lydia' };
// ES5 version:
// var myName = { firstName: 'Lydia' }.firstName;

console.log(myName); // "Lydia"
console.log(firstName); // Uncaught ReferenceError: firstName is not defined
```

Therefore, `firstName` does not exist as a variable, thus attempting to access its value will raise a `ReferenceError`.

**Note:** Be aware of the `global scope` properties:

```javascript
const { name: myName } = { name: 'Lydia' };

console.log(myName); // "lydia"
console.log(name); // "" ----- Browser e.g. Chrome
console.log(name); // ReferenceError: name is not defined  ----- NodeJS
```

Whenever Javascript is unable to find a variable within the _current scope_, it climbs up the [Scope chain](https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/scope-closures/ch3.md) and searches for it and if it reaches the top-level scope, aka **Global scope**, and still doesn't find it, it will throw a `ReferenceError`.

- In **Browsers** such as _Chrome_, `name` is a _deprecated global scope property_. In this example, the code is running inside _global scope_ and there is no user-defined local variable for `name`, therefore it searches the predefined _variables/properties_ in the global scope which is in the case of browsers, it searches through `window` object and it will extract the [window.name](https://developer.mozilla.org/en-US/docs/Web/API/Window/name) value which is equal to an **empty string**.

- In **NodeJS**, there is no such property on the `global` object, thus attempting to access a non-existent variable will raise a [ReferenceError](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors/Not_defined).

</p>
</details>

---

###### 77. Is this a pure function؟

```javascript
function sum(a, b) {
  return a + b;
}
```

- الف: Yes
- ب: No

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

A pure function is a function that _always_ returns the same result, if the same arguments are passed.

The `sum` function always returns the same result. If we pass `1` and `2`, it will _always_ return `3` without side effects. If we pass `5` and `10`, it will _always_ return `15`, and so on. This is the definition of a pure function.

</p>
</details>

---

###### 78. خروجی این کد چیست؟

```javascript
const add = () => {
  const cache = {};
  return (num) => {
    if (num in cache) {
      return `From cache! ${cache[num]}`;
    } else {
      const result = num + 10;
      cache[num] = result;
      return `Calculated! ${result}`;
    }
  };
};

const addFunction = add();
console.log(addFunction(10));
console.log(addFunction(10));
console.log(addFunction(5 * 2));
```

- الف: `Calculated! 20` `Calculated! 20` `Calculated! 20`
- ب: `Calculated! 20` `From cache! 20` `Calculated! 20`
- ج: `Calculated! 20` `From cache! 20` `From cache! 20`
- د: `Calculated! 20` `From cache! 20` `Error`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `add` function is a _memoized_ function. With memoization, we can cache the results of a function in order to speed up its execution. In this case, we create a `cache` object that stores the previously returned values.

If we call the `addFunction` function again with the same argument, it first checks whether it has already gotten that value in its cache. If that's the case, the cache value will be returned, which saves execution time. Otherwise, if it's not cached, it will calculate the value and store it afterward.

We call the `addFunction` function three times with the same value: on the first invocation, the value of the function when `num` is equal to `10` isn't cached yet. The condition of the if-statement `num in cache` returns `false`, and the else block gets executed: `Calculated! 20` gets logged, and the value of the result gets added to the cache object. `cache` now looks like `{ 10: 20 }`.

The second time, the `cache` object contains the value that gets returned for `10`. The condition of the if-statement `num in cache` returns `true`, and `'From cache! 20'` gets logged.

The third time, we pass `5 * 2` to the function which gets evaluated to `10`. The `cache` object contains the value that gets returned for `10`. The condition of the if-statement `num in cache` returns `true`, and `'From cache! 20'` gets logged.

</p>
</details>

---

###### 79. خروجی این کد چیست؟

```javascript
const myLifeSummedUp = ['☕', '💻', '🍷', '🍫'];

for (let item in myLifeSummedUp) {
  console.log(item);
}

for (let item of myLifeSummedUp) {
  console.log(item);
}
```

- الف: `0` `1` `2` `3` and `"☕"` `"💻"` `"🍷"` `"🍫"`
- ب: `"☕"` `"💻"` `"🍷"` `"🍫"` and `"☕"` `"💻"` `"🍷"` `"🍫"`
- ج: `"☕"` `"💻"` `"🍷"` `"🍫"` and `0` `1` `2` `3`
- د: `0` `1` `2` `3` and `{0: "☕", 1: "💻", 2: "🍷", 3: "🍫"}`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

With a _for-in_ loop, we can iterate over **enumerable** properties. In an array, the enumerable properties are the "keys" of array elements, which are actually their indexes. You could see an array as:

`{0: "☕", 1: "💻", 2: "🍷", 3: "🍫"}`

Where the keys are the enumerable properties. `0` `1` `2` `3` get logged.

With a _for-of_ loop, we can iterate over **iterables**. An array is an iterable. When we iterate over the array, the variable "item" is equal to the element it's currently iterating over, `"☕"` `"💻"` `"🍷"` `"🍫"` get logged.

</p>
</details>

---

###### 80. خروجی این کد چیست؟

```javascript
const list = [1 + 2, 1 * 2, 1 / 2];
console.log(list);
```

- الف: `["1 + 2", "1 * 2", "1 / 2"]`
- ب: `["12", 2, 0.5]`
- ج: `[3, 2, 0.5]`
- د: `[1, 1, 1]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Array elements can hold any value. Numbers, strings, objects, other arrays, null, boolean values, undefined, and other expressions such as dates, functions, and calculations.

The element will be equal to the returned value. `1 + 2` returns `3`, `1 * 2` returns `2`, and `1 / 2` returns `0.5`.

</p>
</details>

---

###### 81. خروجی این کد چیست؟

```javascript
function sayHi(name) {
  return `Hi there, ${name}`;
}

console.log(sayHi());
```

- الف: `Hi there,`
- ب: `Hi there, undefined`
- ج: `Hi there, null`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

By default, arguments have the value of `undefined`, unless a value has been passed to the function. In this case, we didn't pass a value for the `name` argument. `name` is equal to `undefined` which gets logged.

In ES6, we can overwrite this default `undefined` value with default parameters. For example:

`function sayHi(name = "Lydia") { ... }`

In this case, if we didn't pass a value or if we passed `undefined`, `name` would always be equal to the string `Lydia`

</p>
</details>

---

###### 82. خروجی این کد چیست؟

```javascript
var status = '😎';

setTimeout(() => {
  const status = '😍';

  const data = {
    status: '🥑',
    getStatus() {
      return this.status;
    },
  };

  console.log(data.getStatus());
  console.log(data.getStatus.call(this));
}, 0);
```

- الف: `"🥑"` and `"😍"`
- ب: `"🥑"` and `"😎"`
- ج: `"😍"` and `"😎"`
- د: `"😎"` and `"😎"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

The value of the `this` keyword is dependent on where you use it. In a **method**, like the `getStatus` method, the `this` keyword refers to _the object that the method belongs to_. The method belongs to the `data` object, so `this` refers to the `data` object. When we log `this.status`, the `status` property on the `data` object gets logged, which is `"🥑"`.

With the `call` method, we can change the object to which the `this` keyword refers. In **functions**, the `this` keyword refers to the _the object that the function belongs to_. We declared the `setTimeout` function on the _global object_, so within the `setTimeout` function, the `this` keyword refers to the _global object_. On the global object, there is a variable called _status_ with the value of `"😎"`. When logging `this.status`, `"😎"` gets logged.

</p>
</details>

---

###### 83. خروجی این کد چیست؟

```javascript
const person = {
  name: 'Lydia',
  age: 21,
};

let city = person.city;
city = 'Amsterdam';

console.log(person);
```

- الف: `{ name: "Lydia", age: 21 }`
- ب: `{ name: "Lydia", age: 21, city: "Amsterdam" }`
- ج: `{ name: "Lydia", age: 21, city: undefined }`
- د: `"Amsterdam"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

We set the variable `city` equal to the value of the property called `city` on the `person` object. There is no property on this object called `city`, so the variable `city` has the value of `undefined`.

Note that we are _not_ referencing the `person` object itself! We simply set the variable `city` equal to the current value of the `city` property on the `person` object.

Then, we set `city` equal to the string `"Amsterdam"`. This doesn't change the person object: there is no reference to that object.

When logging the `person` object, the unmodified object gets returned.

</p>
</details>

---

###### 84. خروجی این کد چیست؟

```javascript
function checkAge(age) {
  if (age < 18) {
    const message = "Sorry, you're too young.";
  } else {
    const message = "Yay! You're old enough!";
  }

  return message;
}

console.log(checkAge(21));
```

- الف: `"Sorry, you're too young."`
- ب: `"Yay! You're old enough!"`
- ج: `ReferenceError`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Variables with the `const` and `let` keywords are _block-scoped_. A block is anything between curly brackets (`{ }`). In this case, the curly brackets of the if/else statements. You cannot reference a variable outside of the block it's declared in, a ReferenceError gets thrown.

</p>
</details>

---

###### 85. چه نوع اطلاعاتی لاگ می‌شود؟

```javascript
fetch('https://www.website.com/api/user/1')
  .then((res) => res.json())
  .then((res) => console.log(res));
```

- الف: The result of the `fetch` method.
- ب: The result of the second invocation of the `fetch` method.
- ج: The result of the callback in the previous `.then()`.
- د: It would always be undefined.

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The value of `res` in the second `.then` is equal to the returned value of the previous `.then`. You can keep chaining `.then`s like this, where the value is passed to the next handler.

</p>
</details>

---

###### 86. کدام گزینه راهی است برای تنظیم `hasName` برابر با `true`, با فرض اینکه نمی‌توانید `true` را به عنوان آرگومان ارسال کنید؟

```javascript
function getName(name) {
  const hasName = //
}
```

- الف: `!!name`
- ب: `name`
- ج: `new Boolean(name)`
- د: `name.length`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

With `!!name`, we determine whether the value of `name` is truthy or falsy. If the name is truthy, which we want to test for, `!name` returns `false`. `!false` (which is what `!!name` practically is) returns `true`.

By setting `hasName` equal to `name`, you set `hasName` equal to whatever value you passed to the `getName` function, not the boolean value `true`.

`new Boolean(true)` returns an object wrapper, not the boolean value itself.

`name.length` returns the length of the passed argument, not whether it's `true`.

</p>
</details>

---

###### 87. خروجی این کد چیست؟

```javascript
console.log('I want pizza'[0]);
```

- الف: `"""`
- ب: `"I"`
- ج: `SyntaxError`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

In order to get a character at a specific index of a string, you can use bracket notation. The first character in the string has index 0, and so on. In this case, we want to get the element with index 0, the character `"I'`, which gets logged.

Note that this method is not supported in IE7 and below. In that case, use `.charAt()`.

</p>
</details>

---

###### 88. خروجی این کد چیست؟

```javascript
function sum(num1, num2 = num1) {
  console.log(num1 + num2);
}

sum(10);
```

- الف: `NaN`
- ب: `20`
- ج: `ReferenceError`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

You can set a default parameter's value equal to another parameter of the function, as long as they've been defined _before_ the default parameter. We pass the value `10` to the `sum` function. If the `sum` function only receives 1 argument, it means that the value for `num2` is not passed, and the value of `num1` is equal to the passed value `10` in this case. The default value of `num2` is the value of `num1`, which is `10`. `num1 + num2` returns `20`.

If you're trying to set a default parameter's value equal to a parameter that is defined _after_ (to the right), the parameter's value hasn't been initialized yet, which will throw an error.

</p>
</details>

---

###### 89. خروجی این کد چیست؟

```javascript
// module.js
export default () => 'Hello world';
export const name = 'Lydia';

// index.js
import * as data from './module';

console.log(data);
```

- الف: `{ default: function default(), name: "Lydia" }`
- ب: `{ default: function default() }`
- ج: `{ default: "Hello world", name: "Lydia" }`
- د: Global object of `module.js`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

With the `import * as name` syntax, we import _all exports_ from the `module.js` file into the `index.js` file as a new object called `data` is created. In the `module.js` file, there are two exports: the default export, and a named export. The default export is a function that returns the string `"Hello World"`, and the named export is a variable called `name` which has the value of the string `"Lydia"`.

The `data` object has a `default` property for the default export, other properties have the names of the named exports and their corresponding values.

</p>
</details>

---

###### 90. خروجی این کد چیست؟

```javascript
class Person {
  constructor(name) {
    this.name = name;
  }
}

const member = new Person('John');
console.log(typeof member);
```

- الف: `"class"`
- ب: `"function"`
- ج: `"object"`
- د: `"string"`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Classes are syntactical sugar for function constructors. The equivalent of the `Person` class as a function constructor would be:

```javascript
function Person(name) {
  this.name = name;
}
```

Calling a function constructor with `new` results in the creation of an instance of `Person`, `typeof` keyword returns `"object"` for an instance. `typeof member` returns `"object"`.

</p>
</details>

---

###### 91. خروجی این کد چیست؟

```javascript
let newList = [1, 2, 3].push(4);

console.log(newList.push(5));
```

- الف: `[1, 2, 3, 4, 5]`
- ب: `[1, 2, 3, 5]`
- ج: `[1, 2, 3, 4]`
- د: `Error`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The `.push` method returns the _new length_ of the array, not the array itself! By setting `newList` equal to `[1, 2, 3].push(4)`, we set `newList` equal to the new length of the array: `4`.

Then, we try to use the `.push` method on `newList`. Since `newList` is the numerical value `4`, we cannot use the `.push` method: a TypeError is thrown.

</p>
</details>

---

###### 92. خروجی این کد چیست؟

```javascript
function giveLydiaPizza() {
  return 'Here is pizza!';
}

const giveLydiaChocolate = () => "Here's chocolate... now go hit the gym already.";

console.log(giveLydiaPizza.prototype);
console.log(giveLydiaChocolate.prototype);
```

- الف: `{ constructor: ...}` `{ constructor: ...}`
- ب: `{}` `{ constructor: ...}`
- ج: `{ constructor: ...}` `{}`
- د: `{ constructor: ...}` `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

Regular functions, such as the `giveLydiaPizza` function, have a `prototype` property, which is an object (prototype object) with a `constructor` property. Arrow functions however, such as the `giveLydiaChocolate` function, do not have this `prototype` property. `undefined` gets returned when trying to access the `prototype` property using `giveLydiaChocolate.prototype`.

</p>
</details>

---

###### 93. خروجی این کد چیست؟

```javascript
const person = {
  name: 'Lydia',
  age: 21,
};

for (const [x, y] of Object.entries(person)) {
  console.log(x, y);
}
```

- الف: `name` `Lydia` and `age` `21`
- ب: `["name", "Lydia"]` and `["age", 21]`
- ج: `["name", "age"]` and `undefined`
- د: `Error`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

`Object.entries(person)` returns an array of nested arrays, containing the keys and objects:

`[ [ 'name', 'Lydia' ], [ 'age', 21 ] ]`

Using the `for-of` loop, we can iterate over each element in the array, the subarrays in this case. We can destructure the subarrays instantly in the for-of loop, using `const [x, y]`. `x` is equal to the first element in the subarray, `y` is equal to the second element in the subarray.

The first subarray is `[ "name", "Lydia" ]`, with `x` equal to `"name"`, and `y` equal to `"Lydia"`, which get logged.
The second subarray is `[ "age", 21 ]`, with `x` equal to `"age"`, and `y` equal to `21`, which get logged.

</p>
</details>

---

###### 94. خروجی این کد چیست؟

```javascript
function getItems(fruitList, ...args, favoriteFruit) {
  return [...fruitList, ...args, favoriteFruit]
}

getItems(["banana", "apple"], "pear", "orange")
```

- الف: `["banana", "apple", "pear", "orange"]`
- ب: `[["banana", "apple"], "pear", "orange"]`
- ج: `["banana", "apple", ["pear"], "orange"]`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

`...args` is a rest parameter. The rest parameter's value is an array containing all remaining arguments, **and can only be the last parameter**! In this example, the rest parameter was the second parameter. This is not possible, and will throw a syntax error.

```javascript
function getItems(fruitList, favoriteFruit, ...args) {
  return [...fruitList, ...args, favoriteFruit];
}

getItems(['banana', 'apple'], 'pear', 'orange');
```

The above example works. This returns the array `[ 'banana', 'apple', 'orange', 'pear' ]`

</p>
</details>

---

###### 95. خروجی این کد چیست؟

```javascript
function nums(a, b) {
  if (a > b) console.log('a is bigger');
  else console.log('b is bigger');
  return;
  a + b;
}

console.log(nums(4, 2));
console.log(nums(1, 2));
```

- الف: `a is bigger`, `6` and `b is bigger`, `3`
- ب: `a is bigger`, `undefined` and `b is bigger`, `undefined`
- ج: `undefined` and `undefined`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

In JavaScript, we don't _have_ to write the semicolon (`;`) explicitly, however the JavaScript engine still adds them after statements. This is called **Automatic Semicolon Insertion**. A statement can for example be variables, or keywords like `throw`, `return`, `break`, etc.

Here, we wrote a `return` statement, and another value `a + b` on a _new line_. However, since it's a new line, the engine doesn't know that it's actually the value that we wanted to return. Instead, it automatically added a semicolon after `return`. You could see this as:

```javascript
return;
a + b;
```

This means that `a + b` is never reached, since a function stops running after the `return` keyword. If no value gets returned, like here, the function returns `undefined`. Note that there is no automatic insertion after `if/else` statements!

</p>
</details>

---

###### 96. خروجی این کد چیست؟

```javascript
class Person {
  constructor() {
    this.name = 'Lydia';
  }
}

Person = class AnotherPerson {
  constructor() {
    this.name = 'Sarah';
  }
};

const member = new Person();
console.log(member.name);
```

- الف: `"Lydia"`
- ب: `"Sarah"`
- ج: `Error: cannot redeclare Person`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

We can set classes equal to other classes/function constructors. In this case, we set `Person` equal to `AnotherPerson`. The name on this constructor is `Sarah`, so the name property on the new `Person` instance `member` is `"Sarah"`.

</p>
</details>

---

###### 97. خروجی این کد چیست؟

```javascript
const info = {
  [Symbol('a')]: 'b',
};

console.log(info);
console.log(Object.keys(info));
```

- الف: `{Symbol('a'): 'b'}` and `["{Symbol('a')"]`
- ب: `{}` and `[]`
- ج: `{ a: "b" }` and `["a"]`
- د: `{Symbol('a'): 'b'}` and `[]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

A Symbol is not _enumerable_. The Object.keys method returns all _enumerable_ key properties on an object. The Symbol won't be visible, and an empty array is returned. When logging the entire object, all properties will be visible, even non-enumerable ones.

This is one of the many qualities of a symbol: besides representing an entirely unique value (which prevents accidental name collision on objects, for example when working with 2 libraries that want to add properties to the same object), you can also "hide" properties on objects this way (although not entirely. You can still access symbols using the `Object.getOwnPropertySymbols()` method).

</p>
</details>

---

###### 98. خروجی این کد چیست؟

```javascript
const getList = ([x, ...y]) => [x, y]
const getUser = user => { name: user.name, age: user.age }

const list = [1, 2, 3, 4]
const user = { name: "Lydia", age: 21 }

console.log(getList(list))
console.log(getUser(user))
```

- الف: `[1, [2, 3, 4]]` and `SyntaxError`
- ب: `[1, [2, 3, 4]]` and `{ name: "Lydia", age: 21 }`
- ج: `[1, 2, 3, 4]` and `{ name: "Lydia", age: 21 }`
- د: `Error` and `{ name: "Lydia", age: 21 }`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The `getList` function receives an array as its argument. Between the parentheses of the `getList` function, we destructure this array right away. You could see this as:

`[x, ...y] = [1, 2, 3, 4]`

With the rest parameter `...y`, we put all "remaining" arguments in an array. The remaining arguments are `2`, `3` and `4` in this case. The value of `y` is an array, containing all the rest parameters. The value of `x` is equal to `1` in this case, so when we log `[x, y]`, `[1, [2, 3, 4]]` gets logged.

The `getUser` function receives an object. With arrow functions, we don't _have_ to write curly brackets if we just return one value. However, if you want to instantly return an _object_ from an arrow function, you have to write it between parentheses, otherwise everything between the two braces will be interpreted as a block statement. In this case the code between the braces is not a valid JavaScript code, so a `SyntaxError` gets thrown.

The following function would have returned an object:

`const getUser = user => ({ name: user.name, age: user.age })`

</p>
</details>

---

###### 99. خروجی این کد چیست؟

```javascript
const name = 'Lydia';

console.log(name());
```

- الف: `SyntaxError`
- ب: `ReferenceError`
- ج: `TypeError`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The variable `name` holds the value of a string, which is not a function, and thus cannot be invoked.

TypeErrors get thrown when a value is not of the expected type. JavaScript expected `name` to be a function since we're trying to invoke it. It was a string however, so a TypeError gets thrown: name is not a function!

SyntaxErrors get thrown when you've written something that isn't valid JavaScript, for example when you've written the word `return` as `retrun`.
ReferenceErrors get thrown when JavaScript isn't able to find a reference to a value that you're trying to access.

</p>
</details>

---

###### 100. مقدار خروجی این کد چیست؟

```javascript
// 🎉✨ This is my 100th question! ✨🎉

const output = `${[] && 'Im'}possible!
You should${'' && `n't`} see a therapist after so much JavaScript lol`;
```

- الف: `possible! You should see a therapist after so much JavaScript lol`
- ب: `Impossible! You should see a therapist after so much JavaScript lol`
- ج: `possible! You shouldn't see a therapist after so much JavaScript lol`
- د: `Impossible! You shouldn't see a therapist after so much JavaScript lol`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

`[]` is a truthy value. With the `&&` operator, the right-hand value will be returned if the left-hand value is a truthy value. In this case, the left-hand value `[]` is a truthy value, so `"Im'` gets returned.

`""` is a falsy value. If the left-hand value is falsy, nothing gets returned. `n't` doesn't get returned.

</p>
</details>

---

###### 101. مقدار خروجی این کد چیست؟

```javascript
const one = false || {} || null;
const two = null || false || '';
const three = [] || 0 || true;

console.log(one, two, three);
```

- الف: `false` `null` `[]`
- ب: `null` `""` `true`
- ج: `{}` `""` `[]`
- د: `null` `null` `true`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With the `||` operator, we can return the first truthy operand. If all values are falsy, the last operand gets returned.

`(false || {} || null)`: the empty object `{}` is a truthy value. This is the first (and only) truthy value, which gets returned. `one` is equal to `{}`.

`(null || false || "")`: all operands are falsy values. This means that the last operand, `""` gets returned. `two` is equal to `""`.

`([] || 0 || "")`: the empty array`[]` is a truthy value. This is the first truthy value, which gets returned. `three` is equal to `[]`.

</p>
</details>

---

###### 102. مقدار خروجی این کد چیست؟

```javascript
const myPromise = () => Promise.resolve('I have resolved!');

function firstFunction() {
  myPromise().then((res) => console.log(res));
  console.log('second');
}

async function secondFunction() {
  console.log(await myPromise());
  console.log('second');
}

firstFunction();
secondFunction();
```

- الف: `I have resolved!`, `second` and `I have resolved!`, `second`
- ب: `second`, `I have resolved!` and `second`, `I have resolved!`
- ج: `I have resolved!`, `second` and `second`, `I have resolved!`
- د: `second`, `I have resolved!` and `I have resolved!`, `second`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

With a promise, we basically say _I want to execute this function, but I'll put it aside for now while it's running since this might take a while. Only when a certain value is resolved (or rejected), and when the call stack is empty, I want to use this value._

We can get this value with both `.then` and the `await` keywords in an `async` function. Although we can get a promise's value with both `.then` and `await`, they work a bit differently.

In the `firstFunction`, we (sort of) put the myPromise function aside while it was running, but continued running the other code, which is `console.log('second')` in this case. Then, the function resolved with the string `I have resolved`, which then got logged after it saw that the callstack was empty.

With the await keyword in `secondFunction`, we literally pause the execution of an async function until the value has been resolved before moving to the next line.

This means that it waited for the `myPromise` to resolve with the value `I have resolved`, and only once that happened, we moved to the next line: `second` got logged.

</p>
</details>

---

###### 103. مقدار خروجی این کد چیست؟

```javascript
const set = new Set();

set.add(1);
set.add('Lydia');
set.add({ name: 'Lydia' });

for (let item of set) {
  console.log(item + 2);
}
```

- الف: `3`, `NaN`, `NaN`
- ب: `3`, `7`, `NaN`
- ج: `3`, `Lydia2`, `[object Object]2`
- د: `"12"`, `Lydia2`, `[object Object]2`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `+` operator is not only used for adding numerical values, but we can also use it to concatenate strings. Whenever the JavaScript engine sees that one or more values are not a number, it coerces the number into a string.

The first one is `1`, which is a numerical value. `1 + 2` returns the number 3.

However, the second one is a string `"Lydia"`. `"Lydia"` is a string and `2` is a number: `2` gets coerced into a string. `"Lydia"` and `"2"` get concatenated, which results in the string `"Lydia2"`.

`{ name: "Lydia" }` is an object. Neither a number nor an object is a string, so it stringifies both. Whenever we stringify a regular object, it becomes `"[object Object]"`. `"[object Object]"` concatenated with `"2"` becomes `"[object Object]2"`.

</p>
</details>

---

###### 104. مقدار این کد چیست؟

```javascript
Promise.resolve(5);
```

- الف: `5`
- ب: `Promise {<pending>: 5}`
- ج: `Promise {<fulfilled>: 5}`
- د: `Error`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

We can pass any type of value we want to `Promise.resolve`, either a promise or a non-promise. The method itself returns a promise with the resolved value (`<fulfilled>`). If you pass a regular function, it'll be a resolved promise with a regular value. If you pass a promise, it'll be a resolved promise with the resolved value of that passed promise.

In this case, we just passed the numerical value `5`. It returns a resolved promise with the value `5`.

</p>
</details>

---

###### 105. مقدار این کد چیست؟

```javascript
function compareMembers(person1, person2 = person) {
  if (person1 !== person2) {
    console.log('Not the same!');
  } else {
    console.log('They are the same!');
  }
}

const person = { name: 'Lydia' };

compareMembers(person);
```

- الف: `Not the same!`
- ب: `They are the same!`
- ج: `ReferenceError`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

Objects are passed by reference. When we check objects for strict equality (`===`), we're comparing their references.

We set the default value for `person2` equal to the `person` object, and passed the `person` object as the value for `person1`.

This means that both values have a reference to the same spot in memory, thus they are equal.

The code block in the `else` statement gets run, and `They are the same!` gets logged.

</p>
</details>

---

###### 106. مقدار این کد چیست؟

```javascript
const colorConfig = {
  red: true,
  blue: false,
  green: true,
  black: true,
  yellow: false,
};

const colors = ['pink', 'red', 'blue'];

console.log(colorConfig.colors[1]);
```

- الف: `true`
- ب: `false`
- ج: `undefined`
- د: `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

In JavaScript, we have two ways to access properties on an object: bracket notation, or dot notation. In this example, we use dot notation (`colorConfig.colors`) instead of bracket notation (`colorConfig["colors"]`).

With dot notation, JavaScript tries to find the property on the object with that exact name. In this example, JavaScript tries to find a property called `colors` on the `colorConfig` object. There is no property called `colors`, so this returns `undefined`. Then, we try to access the value of the first element by using `[1]`. We cannot do this on a value that's `undefined`, so it throws a `TypeError`: `Cannot read property '1' of undefined`.

JavaScript interprets (or unboxes) statements. When we use bracket notation, it sees the first opening bracket `[` and keeps going until it finds the closing bracket `]`. Only then, it will evaluate the statement. If we would've used `colorConfig[colors[1]]`, it would have returned the value of the `red` property on the `colorConfig` object.

</p>
</details>

---

###### 107. مقدار این کد چیست؟

```javascript
console.log('❤️' === '❤️');
```

- الف: `true`
- ب: `false`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

Under the hood, emojis are unicodes. The unicodes for the heart emoji is `"U+2764 U+FE0F"`. These are always the same for the same emojis, so we're comparing two equal strings to each other, which returns true.

</p>
</details>

---

###### 108. کدام‌یک از این متدها آرایه اصلی را تغییر می‌دهد؟

```javascript
const emojis = ['✨', '🥑', '😍'];

emojis.map((x) => x + '✨');
emojis.filter((x) => x !== '🥑');
emojis.find((x) => x !== '🥑');
emojis.reduce((acc, cur) => acc + '✨');
emojis.slice(1, 2, '✨');
emojis.splice(1, 2, '✨');
```

- الف: `All of them`
- ب: `map` `reduce` `slice` `splice`
- ج: `map` `slice` `splice`
- د: `splice`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

With `splice` method, we modify the original array by deleting, replacing or adding elements. In this case, we removed 2 items from index 1 (we removed `'🥑'` and `'😍'`) and added the ✨ emoji instead.

`map`, `filter` and `slice` return a new array, `find` returns an element, and `reduce` returns a reduced value.

</p>
</details>

---

###### 109. خروجی این کد چیست؟

```javascript
const food = ['🍕', '🍫', '🥑', '🍔'];
const info = { favoriteFood: food[0] };

info.favoriteFood = '🍝';

console.log(food);
```

- الف: `['🍕', '🍫', '🥑', '🍔']`
- ب: `['🍝', '🍫', '🥑', '🍔']`
- ج: `['🍝', '🍕', '🍫', '🥑', '🍔']`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

We set the value of the `favoriteFood` property on the `info` object equal to the string with the pizza emoji, `'🍕'`. A string is a primitive data type. In JavaScript, primitive data types don't interact by reference.

In JavaScript, primitive data types (everything that's not an object) interact by _value_. In this case, we set the value of the `favoriteFood` property on the `info` object equal to the value of the first element in the `food` array, the string with the pizza emoji in this case (`'🍕'`). A string is a primitive data type, and interact by value (see my [blogpost](https://www.theavocoder.com/complete-javascript/2018/12/21/by-value-vs-by-reference) if you're interested in learning more)

Then, we change the value of the `favoriteFood` property on the `info` object. The `food` array hasn't changed, since the value of `favoriteFood` was merely a _copy_ of the value of the first element in the array, and doesn't have a reference to the same spot in memory as the element on `food[0]`. When we log food, it's still the original array, `['🍕', '🍫', '🥑', '🍔']`.

</p>
</details>

---

###### 110. این متد چه کاری انجام می‌دهد؟

```javascript
JSON.parse();
```

- الف: Parses JSON to a JavaScript value
- ب: Parses a JavaScript object to JSON
- ج: Parses any JavaScript value to JSON
- د: Parses JSON to a JavaScript object only

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

With the `JSON.parse()` method, we can parse JSON string to a JavaScript value.

```javascript
// Stringifying a number into valid JSON, then parsing the JSON string to a JavaScript value:
const jsonNumber = JSON.stringify(4); // '4'
JSON.parse(jsonNumber); // 4

// Stringifying an array value into valid JSON, then parsing the JSON string to a JavaScript value:
const jsonArray = JSON.stringify([1, 2, 3]); // '[1, 2, 3]'
JSON.parse(jsonArray); // [1, 2, 3]

// Stringifying an object  into valid JSON, then parsing the JSON string to a JavaScript value:
const jsonArray = JSON.stringify({ name: 'Lydia' }); // '{"name":"Lydia"}'
JSON.parse(jsonArray); // { name: 'Lydia' }
```

</p>
</details>

---

###### 111. خروجی این کد چیست؟

```javascript
let name = 'Lydia';

function getName() {
  console.log(name);
  let name = 'Sarah';
}

getName();
```

- الف: Lydia
- ب: Sarah
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

Each function has its own _execution context_ (or _scope_). The `getName` function first looks within its own context (scope) to see if it contains the variable `name` we're trying to access. In this case, the `getName` function contains its own `name` variable: we declare the variable `name` with the `let` keyword, and with the value of `'Sarah'`.

Variables with the `let` keyword (and `const`) are hoisted, but unlike `var`, don't get <i>initialized</i>. They are not accessible before the line we declare (initialize) them. This is called the "temporal dead zone". When we try to access the variables before they are declared, JavaScript throws a `ReferenceError`.

If we wouldn't have declared the `name` variable within the `getName` function, the javascript engine would've looked down the _scope chain_. The outer scope has a variable called `name` with the value of `Lydia`. In that case, it would've logged `Lydia`.

```javascript
let name = 'Lydia';

function getName() {
  console.log(name);
}

getName(); // Lydia
```

</p>
</details>

---

###### 112. خروجی این کد چیست؟

```javascript
function* generatorOne() {
  yield ['a', 'b', 'c'];
}

function* generatorTwo() {
  yield* ['a', 'b', 'c'];
}

const one = generatorOne();
const two = generatorTwo();

console.log(one.next().value);
console.log(two.next().value);
```

- الف: `a` and `a`
- ب: `a` and `undefined`
- ج: `['a', 'b', 'c']` and `a`
- د: `a` and `['a', 'b', 'c']`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With the `yield` keyword, we `yield` values in a generator function. With the `yield*` keyword, we can yield values from another generator function, or iterable object (for example an array).

In `generatorOne`, we yield the entire array `['a', 'b', 'c']` using the `yield` keyword. The value of `value` property on the object returned by the `next` method on `one` (`one.next().value`) is equal to the entire array `['a', 'b', 'c']`.

```javascript
console.log(one.next().value); // ['a', 'b', 'c']
console.log(one.next().value); // undefined
```

In `generatorTwo`, we use the `yield*` keyword. This means that the first yielded value of `two`, is equal to the first yielded value in the iterator. The iterator is the array `['a', 'b', 'c']`. The first yielded value is `a`, so the first time we call `two.next().value`, `a` is returned.

```javascript
console.log(two.next().value); // 'a'
console.log(two.next().value); // 'b'
console.log(two.next().value); // 'c'
console.log(two.next().value); // undefined
```

</p>
</details>

---

###### 113. خروجی این کد چیست؟

```javascript
console.log(`${((x) => x)('I love')} to program`);
```

- الف: `I love to program`
- ب: `undefined to program`
- ج: `${(x => x)('I love') to program`
- د: `TypeError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

Expressions within template literals are evaluated first. This means that the string will contain the returned value of the expression, the immediately invoked function `(x => x)('I love')` in this case. We pass the value `'I love'` as an argument to the `x => x` arrow function. `x` is equal to `'I love'`, which gets returned. This results in `I love to program`.

</p>
</details>

---

###### 114. چه اتفاقی خواهد افتاد؟

```javascript
let config = {
  alert: setInterval(() => {
    console.log('Alert!');
  }, 1000),
};

config = null;
```

- الف: The `setInterval` callback won't be invoked
- ب: The `setInterval` callback gets invoked once
- ج: The `setInterval` callback will still be called every second
- د: We never invoked `config.alert()`, config is `null`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Normally when we set objects equal to `null`, those objects get _garbage collected_ as there is no reference anymore to that object. However, since the callback function within `setInterval` is an arrow function (thus bound to the `config` object), the callback function still holds a reference to the `config` object.
As long as there is a reference, the object won't get garbage collected.
Since this is an interval, setting `config` to `null` or `delete`-ing `config.alert` won't garbage-collect the interval, so the interval will still be called.
It should be cleared with `clearInterval(config.alert)` to remove it from memory.
Since it was not cleared, the `setInterval` callback function will still get invoked every 1000ms (1s).

</p>
</details>

---

###### 115. کدام متد(ها) مقدار `'Hello world!'` را برمی‌گردانند؟

```javascript
const myMap = new Map();
const myFunc = () => 'greeting';

myMap.set(myFunc, 'Hello world!');

//1
myMap.get('greeting');
//2
myMap.get(myFunc);
//3
myMap.get(() => 'greeting');
```

- الف: 1
- ب: 2
- ج: 2 and 3
- د: All of them

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

When adding a key/value pair using the `set` method, the key will be the value of the first argument passed to the `set` function, and the value will be the second argument passed to the `set` function. The key is the _function_ `() => 'greeting'` in this case, and the value `'Hello world'`. `myMap` is now `{ () => 'greeting' => 'Hello world!' }`.

1 is wrong, since the key is not `'greeting'` but `() => 'greeting'`.
3 is wrong, since we're creating a new function by passing it as a parameter to the `get` method. Object interacts by _reference_. Functions are objects, which is why two functions are never strictly equal, even if they are identical: they have a reference to a different spot in memory.

</p>
</details>

---

###### 116. خروجی این کد چیست؟

```javascript
const person = {
  name: 'Lydia',
  age: 21,
};

const changeAge = (x = { ...person }) => (x.age += 1);
const changeAgeAndName = (x = { ...person }) => {
  x.age += 1;
  x.name = 'Sarah';
};

changeAge(person);
changeAgeAndName();

console.log(person);
```

- الف: `{name: "Sarah", age: 22}`
- ب: `{name: "Sarah", age: 23}`
- ج: `{name: "Lydia", age: 22}`
- د: `{name: "Lydia", age: 23}`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Both the `changeAge` and `changeAgeAndName` functions have a default parameter, namely a _newly_ created object `{ ...person }`. This object has copies of all the key/values in the `person` object.

First, we invoke the `changeAge` function and pass the `person` object as its argument. This function increases the value of the `age` property by 1. `person` is now `{ name: "Lydia", age: 22 }`.

Then, we invoke the `changeAgeAndName` function, however we don't pass a parameter. Instead, the value of `x` is equal to a _new_ object: `{ ...person }`. Since it's a new object, it doesn't affect the values of the properties on the `person` object. `person` is still equal to `{ name: "Lydia", age: 22 }`.

</p>
</details>

---

###### 117. کدام‌یک از گزینه‌های زیر مقدار `6` را برمی‌گرداند؟

```javascript
function sumValues(x, y, z) {
  return x + y + z;
}
```

- الف: `sumValues([...1, 2, 3])`
- ب: `sumValues([...[1, 2, 3]])`
- ج: `sumValues(...[1, 2, 3])`
- د: `sumValues([1, 2, 3])`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With the spread operator `...`, we can _spread_ iterables to individual elements. The `sumValues` function receives three arguments: `x`, `y` and `z`. `...[1, 2, 3]` will result in `1, 2, 3`, which we pass to the `sumValues` function.

</p>
</details>

---

###### 118. خروجی این کد چیست؟

```javascript
let num = 1;
const list = ['🥳', '🤠', '🥰', '🤪'];

console.log(list[(num += 1)]);
```

- الف: `🤠`
- ب: `🥰`
- ج: `SyntaxError`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the `+=` operator, we're incrementing the value of `num` by `1`. `num` had the initial value `1`, so `1 + 1` is `2`. The item on the second index in the `list` array is 🥰, `console.log(list[2])` prints 🥰.

</p>
</details>

---

###### 119. خروجی این کد چیست؟

```javascript
const person = {
  firstName: 'Lydia',
  lastName: 'Hallie',
  pet: {
    name: 'Mara',
    breed: 'Dutch Tulip Hound',
  },
  getFullName() {
    return `${this.firstName} ${this.lastName}`;
  },
};

console.log(person.pet؟.name);
console.log(person.pet؟.family؟.name);
console.log(person.getFullName؟.());
console.log(member.getLastName؟.());
```

- الف: `undefined` `undefined` `undefined` `undefined`
- ب: `Mara` `undefined` `Lydia Hallie` `ReferenceError`
- ج: `Mara` `null` `Lydia Hallie` `null`
- د: `null` `ReferenceError` `null` `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the optional chaining operator `؟.`, we no longer have to explicitly check whether the deeper nested values are valid or not. If we're trying to access a property on an `undefined` or `null` value (_nullish_), the expression short-circuits and returns `undefined`.

`person.pet؟.name`: `person` has a property named `pet`: `person.pet` is not nullish. It has a property called `name`, and returns `Mara`.
`person.pet؟.family؟.name`: `person` has a property named `pet`: `person.pet` is not nullish. `pet` does _not_ have a property called `family`, `person.pet.family` is nullish. The expression returns `undefined`.
`person.getFullName؟.()`: `person` has a property named `getFullName`: `person.getFullName()` is not nullish and can get invoked, which returns `Lydia Hallie`.
`member.getLastName؟.()`: variable `member` is non-existent therefore a `ReferenceError` gets thrown!

</p>
</details>

---

###### 120. خروجی این کد چیست؟

```javascript
const groceries = ['banana', 'apple', 'peanuts'];

if (groceries.indexOf('banana')) {
  console.log('We have to buy bananas!');
} else {
  console.log(`We don't have to buy bananas!`);
}
```

- الف: We have to buy bananas!
- ب: We don't have to buy bananas
- ج: `undefined`
- د: `1`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

We passed the condition `groceries.indexOf("banana")` to the if-statement. `groceries.indexOf("banana")` returns `0`, which is a falsy value. Since the condition in the if-statement is falsy, the code in the `else` block runs, and `We don't have to buy bananas!` gets logged.

</p>
</details>

---

###### 121. خروجی این کد چیست؟

```javascript
const config = {
  languages: [],
  set language(lang) {
    return this.languages.push(lang);
  },
};

console.log(config.language);
```

- الف: `function language(lang) { this.languages.push(lang }`
- ب: `0`
- ج: `[]`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The `language` method is a `setter`. Setters don't hold an actual value, their purpose is to _modify_ properties. When calling a `setter` method, `undefined` gets returned.

</p>
</details>

---

###### 122. خروجی این کد چیست؟

```javascript
const name = 'Lydia Hallie';

console.log(!typeof name === 'object');
console.log(!typeof name === 'string');
```

- الف: `false` `true`
- ب: `true` `false`
- ج: `false` `false`
- د: `true` `true`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

`typeof name` returns `"string"`. The string `"string"` is a truthy value, so `!typeof name` returns the boolean value `false`. `false === "object"` and `false === "string"` both return`false`.

(If we wanted to check whether the type was (un)equal to a certain type, we should've written `!==` instead of `!typeof`)

</p>
</details>

---

###### 123. خروجی این کد چیست؟

```javascript
const add = (x) => (y) => (z) => {
  console.log(x, y, z);
  return x + y + z;
};

add(4)(5)(6);
```

- الف: `4` `5` `6`
- ب: `6` `5` `4`
- ج: `4` `function` `function`
- د: `undefined` `undefined` `6`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The `add` function returns an arrow function, which returns an arrow function, which returns an arrow function (still with me؟). The first function receives an argument `x` with the value of `4`. We invoke the second function, which receives an argument `y` with the value `5`. Then we invoke the third function, which receives an argument `z` with the value `6`. When we're trying to access the value `x`, `y` and `z` within the last arrow function, the JS engine goes up the scope chain in order to find the values for `x` and `y` accordingly. This returns `4` `5` `6`.

</p>
</details>

---

###### 124. خروجی این کد چیست؟

```javascript
async function* range(start, end) {
  for (let i = start; i <= end; i++) {
    yield Promise.resolve(i);
  }
}

(async () => {
  const gen = range(1, 3);
  for await (const item of gen) {
    console.log(item);
  }
})();
```

- الف: `Promise {1}` `Promise {2}` `Promise {3}`
- ب: `Promise {<pending>}` `Promise {<pending>}` `Promise {<pending>}`
- ج: `1` `2` `3`
- د: `undefined` `undefined` `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The generator function `range` returns an async object with promises for each item in the range we pass: `Promise{1}`, `Promise{2}`, `Promise{3}`. We set the variable `gen` equal to the async object, after which we loop over it using a `for await ... of` loop. We set the variable `item` equal to the returned Promise values: first `Promise{1}`, then `Promise{2}`, then `Promise{3}`. Since we're _awaiting_ the value of `item`, the resolved promise, the resolved _values_ of the promises get returned: `1`, `2`, then `3`.

</p>
</details>

---

###### 125. خروجی این کد چیست؟

```javascript
const myFunc = ({ x, y, z }) => {
  console.log(x, y, z);
};

myFunc(1, 2, 3);
```

- الف: `1` `2` `3`
- ب: `{1: 1}` `{2: 2}` `{3: 3}`
- ج: `{ 1: undefined }` `undefined` `undefined`
- د: `undefined` `undefined` `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

`myFunc` expects an object with properties `x`, `y` and `z` as its argument. Since we're only passing three separate numeric values (1, 2, 3) instead of one object with properties `x`, `y` and `z` ({x: 1, y: 2, z: 3}), `x`, `y` and `z` have their default value of `undefined`.

</p>
</details>

---

###### 126. خروجی این کد چیست؟

```javascript
function getFine(speed, amount) {
  const formattedSpeed = new Intl.NumberFormat('en-US', {
    style: 'unit',
    unit: 'mile-per-hour',
  }).format(speed);

  const formattedAmount = new Intl.NumberFormat('en-US', {
    style: 'currency',
    currency: 'USD',
  }).format(amount);

  return `The driver drove ${formattedSpeed} and has to pay ${formattedAmount}`;
}

console.log(getFine(130, 300));
```

- الف: The driver drove 130 and has to pay 300
- ب: The driver drove 130 mph and has to pay \$300.00
- ج: The driver drove undefined and has to pay undefined
- د: The driver drove 130.00 and has to pay 300.00

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the `Intl.NumberFormat` method, we can format numeric values to any locale. We format the numeric value `130` to the `en-US` locale as a `unit` in `mile-per-hour`, which results in `130 mph`. The numeric value `300` to the `en-US` locale as a `currency` in `USD` results in `$300.00`.

</p>
</details>

---

###### 127. خروجی این کد چیست؟

```javascript
const spookyItems = ['👻', '🎃', '🕸'];
({ item: spookyItems[3] } = { item: '💀' });

console.log(spookyItems);
```

- الف: `["👻", "🎃", "🕸"]`
- ب: `["👻", "🎃", "🕸", "💀"]`
- ج: `["👻", "🎃", "🕸", { item: "💀" }]`
- د: `["👻", "🎃", "🕸", "[object Object]"]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

By destructuring objects, we can unpack values from the right-hand object, and assign the unpacked value to the value of the same property name on the left-hand object. In this case, we're assigning the value "💀" to `spookyItems[3]`. This means that we're modifying the `spookyItems` array, we're adding the "💀" to it. When logging `spookyItems`, `["👻", "🎃", "🕸", "💀"]` gets logged.

</p>
</details>

---

###### 128. خروجی این کد چیست؟

```javascript
const name = 'Lydia Hallie';
const age = 21;

console.log(Number.isNaN(name));
console.log(Number.isNaN(age));

console.log(isNaN(name));
console.log(isNaN(age));
```

- الف: `true` `false` `true` `false`
- ب: `true` `false` `false` `false`
- ج: `false` `false` `true` `false`
- د: `false` `true` `false` `true`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With the `Number.isNaN` method, you can check if the value you pass is a _numeric value_ and equal to `NaN`. `name` is not a numeric value, so `Number.isNaN(name)` returns `false`. `age` is a numeric value, but is not equal to `NaN`, so `Number.isNaN(age)` returns `false`.

With the `isNaN` method, you can check if the value you pass is not a number. `name` is not a number, so `isNaN(name)` returns true. `age` is a number, so `isNaN(age)` returns `false`.

</p>
</details>

---

###### 129. خروجی این کد چیست؟

```javascript
const randomValue = 21;

function getInfo() {
  console.log(typeof randomValue);
  const randomValue = 'Lydia Hallie';
}

getInfo();
```

- الف: `"number"`
- ب: `"string"`
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

Variables declared with the `const` keyword are not referenceable before their initialization: this is called the _temporal dead zone_. In the `getInfo` function, the variable `randomValue` is scoped in the functional scope of `getInfo`. On the line where we want to log the value of `typeof randomValue`, the variable `randomValue` isn't initialized yet: a `ReferenceError` gets thrown! The engine didn't go down the scope chain since we declared the variable `randomValue` in the `getInfo` function.

</p>
</details>

---

###### 130. خروجی این کد چیست؟

```javascript
const myPromise = Promise.resolve('Woah some cool data');

(async () => {
  try {
    console.log(await myPromise);
  } catch {
    throw new Error(`Oops didn't work`);
  } finally {
    console.log('Oh finally!');
  }
})();
```

- الف: `Woah some cool data`
- ب: `Oh finally!`
- ج: `Woah some cool data` `Oh finally!`
- د: `Oops didn't work` `Oh finally!`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

In the `try` block, we're logging the awaited value of the `myPromise` variable: `"Woah some cool data"`. Since no errors were thrown in the `try` block, the code in the `catch` block doesn't run. The code in the `finally` block _always_ runs, `"Oh finally!"` gets logged.

</p>
</details>

---

###### 131. خروجی این کد چیست؟

```javascript
const emojis = ['🥑', ['✨', '✨', ['🍕', '🍕']]];

console.log(emojis.flat(1));
```

- الف: `['🥑', ['✨', '✨', ['🍕', '🍕']]]`
- ب: `['🥑', '✨', '✨', ['🍕', '🍕']]`
- ج: `['🥑', ['✨', '✨', '🍕', '🍕']]`
- د: `['🥑', '✨', '✨', '🍕', '🍕']`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

With the `flat` method, we can create a new, flattened array. The depth of the flattened array depends on the value that we pass. In this case, we passed the value `1` (which we didn't have to, that's the default value), meaning that only the arrays on the first depth will be concatenated. `['🥑']` and `['✨', '✨', ['🍕', '🍕']]` in this case. Concatenating these two arrays results in `['🥑', '✨', '✨', ['🍕', '🍕']]`.

</p>
</details>

---

###### 132. خروجی این کد چیست؟

```javascript
class Counter {
  constructor() {
    this.count = 0;
  }

  increment() {
    this.count++;
  }
}

const counterOne = new Counter();
counterOne.increment();
counterOne.increment();

const counterTwo = counterOne;
counterTwo.increment();

console.log(counterOne.count);
```

- الف: `0`
- ب: `1`
- ج: `2`
- د: `3`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

`counterOne` is an instance of the `Counter` class. The counter class contains a `count` property on its constructor, and an `increment` method. First, we invoked the `increment` method twice by calling `counterOne.increment()`. Currently, `counterOne.count` is `2`.

<img src="https://i.imgur.com/KxLlTm9.png" width="400">

Then, we create a new variable `counterTwo`, and set it equal to `counterOne`. Since objects interact by reference, we're just creating a new reference to the same spot in memory that `counterOne` points to. Since it has the same spot in memory, any changes made to the object that `counterTwo` has a reference to, also apply to `counterOne`. Currently, `counterTwo.count` is `2`.

We invoke `counterTwo.increment()`, which sets `count` to `3`. Then, we log the count on `counterOne`, which logs `3`.

<img src="https://i.imgur.com/BNBHXmc.png" width="400">

</p>
</details>

---

###### 133. خروجی این کد چیست؟

```javascript
const myPromise = Promise.resolve(Promise.resolve('Promise'));

function funcOne() {
  setTimeout(() => console.log('Timeout 1!'), 0);
  myPromise.then((res) => res).then((res) => console.log(`${res} 1!`));
  console.log('Last line 1!');
}

async function funcTwo() {
  const res = await myPromise;
  console.log(`${res} 2!`);
  setTimeout(() => console.log('Timeout 2!'), 0);
  console.log('Last line 2!');
}

funcOne();
funcTwo();
```

- الف: `Promise 1! Last line 1! Promise 2! Last line 2! Timeout 1! Timeout 2!`
- ب: `Last line 1! Timeout 1! Promise 1! Last line 2! Promise2! Timeout 2! `
- ج: `Last line 1! Promise 2! Last line 2! Promise 1! Timeout 1! Timeout 2!`
- د: `Timeout 1! Promise 1! Last line 1! Promise 2! Timeout 2! Last line 2!`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

First, we invoke `funcOne`. On the first line of `funcOne`, we call the _asynchronous_ `setTimeout` function, from which the callback is sent to the Web API. (see my article on the event loop <a href="https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif">here</a>.)

Then we call the `myPromise` promise, which is an _asynchronous_ operation. Pay attention, that now only the first then clause was added to the microtask queue.

Both the promise and the timeout are asynchronous operations, the function keeps on running while it's busy completing the promise and handling the `setTimeout` callback. This means that `Last line 1!` gets logged first, since this is not an asynchonous operation.

Since the callstack is not empty yet, the `setTimeout` function and promise in `funcOne` cannot get added to the callstack yet.

In `funcTwo`, the variable `res` gets `Promise` because `Promise.resolve(Promise.resolve('Promise'))` is equivalent to `Promise.resolve('Promise')` since resolving a promise just resolves it's value. The `await` in this line stops the execution of the function until it receives the resolution of the promise and then keeps on running synchronously until completion, so `Promise 2!` and then `Last line 2!` are logged and the `setTimeout` is sent to the Web API. If the first then clause in `funcOne` had its own log statement, it would be printed before `Promise 2!`. Howewer, it executed silently and put the second then clause in microtask queue. So, the second clause will be printed after `Promise 2!`.

Then the call stack is empty. Promises are _microtasks_ so they are resolved first when the call stack is empty so `Promise 1!` gets to be logged.

Now, since `funcTwo` popped off the call stack, the call stack is empty. The callbacks waiting in the queue (`() => console.log("Timeout 1!")` from `funcOne`, and `() => console.log("Timeout 2!")` from `funcTwo`) get added to the call stack one by one. The first callback logs `Timeout 1!`, and gets popped off the stack. Then, the second callback logs `Timeout 2!`, and gets popped off the stack.

</p>
</details>

---

###### 134. How can we invoke `sum` in `sum.js` from `index.js؟`

```javascript
// sum.js
export default function sum(x) {
  return x + x;
}

// index.js
import * as sum from './sum';
```

- الف: `sum(4)`
- ب: `sum.sum(4)`
- ج: `sum.default(4)`
- د: Default aren't imported with `*`, only named exports

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With the asterisk `*`, we import all exported values from that file, both default and named. If we had the following file:

```javascript
// info.js
export const name = 'Lydia';
export const age = 21;
export default 'I love JavaScript';

// index.js
import * as info from './info';
console.log(info);
```

The following would get logged:

```javascript
{
  default: "I love JavaScript",
  name: "Lydia",
  age: 21
}
```

For the `sum` example, it means that the imported value `sum` looks like this:

```javascript
{ default: function sum(x) { return x + x } }
```

We can invoke this function, by calling `sum.default`

</p>
</details>

---

###### 135. خروجی این کد چیست؟

```javascript
const handler = {
  set: () => console.log('Added a new property!'),
  get: () => console.log('Accessed a property!'),
};

const person = new Proxy({}, handler);

person.name = 'Lydia';
person.name;
```

- الف: `Added a new property!`
- ب: `Accessed a property!`
- ج: `Added a new property!` `Accessed a property!`
- د: Nothing gets logged

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

With a Proxy object, we can add custom behavior to an object that we pass to it as the second argument. In this case, we pass the `handler` object which contains two properties: `set` and `get`. `set` gets invoked whenever we _set_ property values, and `get` gets invoked whenever we _get_ (access) property values.

The first argument is an empty object `{}`, which is the value of `person`. To this object, the custom behavior specified in the `handler` object gets added. If we add a property to the `person` object, `set` will get invoked. If we access a property on the `person` object, `get` gets invoked.

First, we added a new property `name` to the proxy object (`person.name = "Lydia"`). `set` gets invoked, and logs `"Added a new property!"`.

Then, we access a property value on the proxy object, and the `get` property on the handler object is invoked. `"Accessed a property!"` gets logged.

</p>
</details>

---

###### 136. کدام‌یک از موارد زیر، شیء `person` را تغییر می‌دهد؟

```javascript
const person = { name: 'Lydia Hallie' };

Object.seal(person);
```

- الف: `person.name = "Evan Bacon"`
- ب: `person.age = 21`
- ج: `delete person.name`
- د: `Object.assign(person, { age: 21 })`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

With `Object.seal` we can prevent new properties from being _added_, or existing properties to be _removed_.

However, you can still modify the value of existing properties.

</p>
</details>

---

###### 137. Which of the following will modify the `person` object؟

```javascript
const person = {
  name: 'Lydia Hallie',
  address: {
    street: '100 Main St',
  },
};

Object.freeze(person);
```

- الف: `person.name = "Evan Bacon"`
- ب: `delete person.address`
- ج: `person.address.street = "101 Main St"`
- د: `person.pet = { name: "Mara" }`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `Object.freeze` method _freezes_ an object. No properties can be added, modified, or removed.

However, it only _shallowly_ freezes the object, meaning that only _direct_ properties on the object are frozen. If the property is another object, like `address` in this case, the properties on that object aren't frozen, and can be modified.

</p>
</details>

---

###### 138. خروجی این کد چیست؟

```javascript
const add = (x) => x + x;

function myFunc(num = 2, value = add(num)) {
  console.log(num, value);
}

myFunc();
myFunc(3);
```

- الف: `2` `4` and `3` `6`
- ب: `2` `NaN` and `3` `NaN`
- ج: `2` `Error` and `3` `6`
- د: `2` `4` and `3` `Error`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

First, we invoked `myFunc()` without passing any arguments. Since we didn't pass arguments, `num` and `value` got their default values: num is `2`, and `value` is the returned value of the function `add`. To the `add` function, we pass `num` as an argument, which had the value of `2`. `add` returns `4`, which is the value of `value`.

Then, we invoked `myFunc(3)` and passed the value `3` as the value for the argument `num`. We didn't pass an argument for `value`. Since we didn't pass a value for the `value` argument, it got the default value: the returned value of the `add` function. To `add`, we pass `num`, which has the value of `3`. `add` returns `6`, which is the value of `value`.

</p>
</details>

---

###### 139. خروجی این کد چیست؟

```javascript
class Counter {
  #number = 10;

  increment() {
    this.#number++;
  }

  getNum() {
    return this.#number;
  }
}

const counter = new Counter();
counter.increment();

console.log(counter.#number);
```

- الف: `10`
- ب: `11`
- ج: `undefined`
- د: `SyntaxError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

In ES2020, we can add private variables in classes by using the `#`. We cannot access these variables outside of the class. When we try to log `counter.#number`, a SyntaxError gets thrown: we cannot access it outside the `Counter` class!

</p>
</details>

---

###### 140. چه چیزی کم است؟

```javascript
const teams = [
  { name: 'Team 1', members: ['Paul', 'Lisa'] },
  { name: 'Team 2', members: ['Laura', 'Tim'] },
];

function* getMembers(members) {
  for (let i = 0; i < members.length; i++) {
    yield members[i];
  }
}

function* getTeams(teams) {
  for (let i = 0; i < teams.length; i++) {
    // ✨ SOMETHING IS MISSING HERE ✨
  }
}

const obj = getTeams(teams);
obj.next(); // { value: "Paul", done: false }
obj.next(); // { value: "Lisa", done: false }
```

- الف: `yield getMembers(teams[i].members)`
- ب: `yield* getMembers(teams[i].members)`
- ج: `return getMembers(teams[i].members)`
- د: `return yield getMembers(teams[i].members)`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

In order to iterate over the `members` in each element in the `teams` array, we need to pass `teams[i].members` to the `getMembers` generator function. The generator function returns a generator object. In order to iterate over each element in this generator object, we need to use `yield*`.

If we would've written `yield`, `return yield`, or `return`, the entire generator function would've gotten returned the first time we called the `next` method.

</p>
</details>

---

###### 141. خروجی این کد چیست؟

```javascript
const person = {
  name: 'Lydia Hallie',
  hobbies: ['coding'],
};

function addHobby(hobby, hobbies = person.hobbies) {
  hobbies.push(hobby);
  return hobbies;
}

addHobby('running', []);
addHobby('dancing');
addHobby('baking', person.hobbies);

console.log(person.hobbies);
```

- الف: `["coding"]`
- ب: `["coding", "dancing"]`
- ج: `["coding", "dancing", "baking"]`
- د: `["coding", "running", "dancing", "baking"]`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `addHobby` function receives two arguments, `hobby` and `hobbies` with the default value of the `hobbies` array on the `person` object.

First, we invoke the `addHobby` function, and pass `"running"` as the value for `hobby` and an empty array as the value for `hobbies`. Since we pass an empty array as the value for `hobbies`, `"running"` gets added to this empty array.

Then, we invoke the `addHobby` function, and pass `"dancing"` as the value for `hobby`. We didn't pass a value for `hobbies`, so it gets the default value, the `hobbies` property on the `person` object. We push the hobby `dancing` to the `person.hobbies` array.

Last, we invoke the `addHobby` function, and pass `"baking"` as the value for `hobby`, and the `person.hobbies` array as the value for `hobbies`. We push the hobby `baking` to the `person.hobbies` array.

After pushing `dancing` and `baking`, the value of `person.hobbies` is `["coding", "dancing", "baking"]`

</p>
</details>

---

###### 142. خروجی این کد چیست؟

```javascript
class Bird {
  constructor() {
    console.log("I'm a bird. 🦢");
  }
}

class Flamingo extends Bird {
  constructor() {
    console.log("I'm pink. 🌸");
    super();
  }
}

const pet = new Flamingo();
```

- الف: `I'm pink. 🌸`
- ب: `I'm pink. 🌸` `I'm a bird. 🦢`
- ج: `I'm a bird. 🦢` `I'm pink. 🌸`
- د: Nothing, we didn't call any method

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

We create the variable `pet` which is an instance of the `Flamingo` class. When we instantiate this instance, the `constructor` on `Flamingo` gets called. First, `"I'm pink. 🌸"` gets logged, after which we call `super()`. `super()` calls the constructor of the parent class, `Bird`. The constructor in `Bird` gets called, and logs `"I'm a bird. 🦢"`.

</p>
</details>

---

###### 143. کدام‌یک از گزینه‌ها منجر به error می‌شود؟

```javascript
const emojis = ['🎄', '🎅🏼', '🎁', '⭐'];

/* 1 */ emojis.push('🦌');
/* 2 */ emojis.splice(0, 2);
/* 3 */ emojis = [...emojis, '🥂'];
/* 4 */ emojis.length = 0;
```

- الف: 1
- ب: 1 and 2
- ج: 3 and 4
- د: 3

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The `const` keyword simply means we cannot _redeclare_ the value of that variable, it's _read-only_. However, the value itself isn't immutable. The properties on the `emojis` array can be modified, for example by pushing new values, splicing them, or setting the length of the array to 0.

</p>
</details>

---

###### 144. برای اینکه خروجی `[...person]` برابر با `["Lydia Hallie", 21]` باشد، چه چیزی باید به شیء `person` اضافه کنیم؟؟

```javascript
const person = {
  name: "Lydia Hallie",
  age: 21
}

[...person] // ["Lydia Hallie", 21]
```

- الف: Nothing, object are iterable by default
- ب: `*[Symbol.iterator]() { for (let x in this) yield* this[x] }`
- ج: `*[Symbol.iterator]() { yield* Object.values(this) }`
- د: `*[Symbol.iterator]() { for (let x in this) yield this }`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

Objects aren't iterable by default. An iterable is an iterable if the iterator protocol is present. We can add this manually by adding the iterator symbol `[Symbol.iterator]`, which has to return a generator object, for example by making it a generator function `*[Symbol.iterator]() {}`. This generator function has to yield the `Object.values` of the `person` object if we want it to return the array `["Lydia Hallie", 21]`: `yield* Object.values(this)`.

</p>
</details>

---

###### 145. خروجی این کد چیست؟

```javascript
let count = 0;
const nums = [0, 1, 2, 3];

nums.forEach((num) => {
  if (num) count += 1;
});

console.log(count);
```

- الف: 1
- ب: 2
- ج: 3
- د: 4

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `if` condition within the `forEach` loop checks whether the value of `num` is truthy or falsy. Since the first number in the `nums` array is `0`, a falsy value, the `if` statement's code block won't be executed. `count` only gets incremented for the other 3 numbers in the `nums` array, `1`, `2` and `3`. Since `count` gets incremented by `1` 3 times, the value of `count` is `3`.

</p>
</details>

---

###### 146. خروجی این کد چیست؟

```javascript
function getFruit(fruits) {
  console.log(fruits؟.[1]؟.[1]);
}

getFruit([['🍊', '🍌'], ['🍍']]);
getFruit();
getFruit([['🍍'], ['🍊', '🍌']]);
```

- الف: `null`, `undefined`, 🍌
- ب: `[]`, `null`, 🍌
- ج: `[]`, `[]`, 🍌
- د: `undefined`, `undefined`, 🍌

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The `؟` allows us to optionally access deeper nested properties within objects. We're trying to log the item on index `1` within the subarray that's on index `1` of the `fruits` array. If the subarray on index `1` in the `fruits` array doesn't exist, it'll simply return `undefined`. If the subarray on index `1` in the `fruits` array exists, but this subarray doesn't have an item on its `1` index, it'll also return `undefined`.

First, we're trying to log the second item in the `['🍍']` subarray of `[['🍊', '🍌'], ['🍍']]`. This subarray only contains one item, which means there is no item on index `1`, and returns `undefined`.

Then, we're invoking the `getFruits` function without passing a value as an argument, which means that `fruits` has a value of `undefined` by default. Since we're conditionally chaining the item on index `1` of`fruits`, it returns `undefined` since this item on index `1` does not exist.

Lastly, we're trying to log the second item in the `['🍊', '🍌']` subarray of `['🍍'], ['🍊', '🍌']`. The item on index `1` within this subarray is `🍌`, which gets logged.

</p>
</details>

---

###### 147. خروجی این کد چیست؟

```javascript
class Calc {
  constructor() {
    this.count = 0;
  }

  increase() {
    this.count++;
  }
}

const calc = new Calc();
new Calc().increase();

console.log(calc.count);
```

- الف: `0`
- ب: `1`
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

We set the variable `calc` equal to a new instance of the `Calc` class. Then, we instantiate a new instance of `Calc`, and invoke the `increase` method on this instance. Since the count property is within the constructor of the `Calc` class, the count property is not shared on the prototype of `Calc`. This means that the value of count has not been updated for the instance calc points to, count is still `0`.

</p>
</details>

---

###### 148. خروجی این کد چیست؟

```javascript
const user = {
  email: 'e@mail.com',
  password: '12345',
};

const updateUser = ({ email, password }) => {
  if (email) {
    Object.assign(user, { email });
  }

  if (password) {
    user.password = password;
  }

  return user;
};

const updatedUser = updateUser({ email: 'new@email.com' });

console.log(updatedUser === user);
```

- الف: `false`
- ب: `true`
- ج: `TypeError`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

The `updateUser` function updates the values of the `email` and `password` properties on user, if their values are passed to the function, after which the function returns the `user` object. The returned value of the `updateUser` function is the `user` object, which means that the value of updatedUser is a reference to the same `user` object that `user` points to. `updatedUser === user` equals `true`.

</p>
</details>

---

###### 149. خروجی این کد چیست؟

```javascript
const fruit = ['🍌', '🍊', '🍎'];

fruit.slice(0, 1);
fruit.splice(0, 1);
fruit.unshift('🍇');

console.log(fruit);
```

- الف: `['🍌', '🍊', '🍎']`
- ب: `['🍊', '🍎']`
- ج: `['🍇', '🍊', '🍎']`
- د: `['🍇', '🍌', '🍊', '🍎']`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

First, we invoke the `slice` method on the fruit array. The slice method does not modify the original array, but returns the value that it sliced off the array: the banana emoji.
Then, we invoke the `splice` method on the fruit array. The splice method does modify the original array, which means that the fruit array now consists of `['🍊', '🍎']`.
At last, we invoke the `unshift` method on the `fruit` array, which modifies the original array by adding the provided value, ‘🍇’ in this case, as the first element in the array. The fruit array now consists of `['🍇', '🍊', '🍎']`.

</p>
</details>

---

###### 150. خروجی این کد چیست؟

```javascript
const animals = {};
let dog = { emoji: '🐶' };
let cat = { emoji: '🐈' };

animals[dog] = { ...dog, name: 'Mara' };
animals[cat] = { ...cat, name: 'Sara' };

console.log(animals[dog]);
```

- الف: `{ emoji: "🐶", name: "Mara" }`
- ب: `{ emoji: "🐈", name: "Sara" }`
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

Object keys are converted to strings.

Since the value of `dog` is an object, `animals[dog]` actually means that we’re creating a new property called `"[object Object]"` equal to the new object. `animals["[object Object]"]` is now equal to `{ emoji: "🐶", name: "Mara"}`.

`cat` is also an object, which means that `animals[cat]` actually means that we’re overwriting the value of `animals["[object Object]"]` with the new cat properties.

Logging `animals[dog]`, or actually `animals["[object Object]"]` since converting the `dog` object to a string results `"[object Object]"`, returns the `{ emoji: "🐈", name: "Sara" }`.

</p>
</details>

---

###### 151. خروجی این کد چیست؟

```javascript
const user = {
  email: 'my@email.com',
  updateEmail: (email) => {
    this.email = email;
  },
};

user.updateEmail('new@email.com');
console.log(user.email);
```

- الف: `my@email.com`
- ب: `new@email.com`
- ج: `undefined`
- د: `ReferenceError`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: الف

The `updateEmail` function is an arrow function, and is not bound to the `user` object. This means that the `this` keyword is not referring to the `user` object, but refers to the global scope in this case. The value of `email` within the `user` object does not get updated. When logging the value of `user.email`, the original value of `my@email.com` gets returned.

</p>
</details>

---

###### 152. خروجی این کد چیست؟

```javascript
const promise1 = Promise.resolve('First');
const promise2 = Promise.resolve('Second');
const promise3 = Promise.reject('Third');
const promise4 = Promise.resolve('Fourth');

const runPromises = async () => {
  const res1 = await Promise.all([promise1, promise2]);
  const res2 = await Promise.all([promise3, promise4]);
  return [res1, res2];
};

runPromises()
  .then((res) => console.log(res))
  .catch((err) => console.log(err));
```

- الف: `[['First', 'Second'], ['Fourth']]`
- ب: `[['First', 'Second'], ['Third', 'Fourth']]`
- ج: `[['First', 'Second']]`
- د: `'Third'`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: د

The `Promise.all` method runs the passed promises in parallel. If one promise fails, the `Promise.all` method _rejects_ with the value of the rejected promise. In this case, `promise3` is rejected with the value `"Third"`. We’re catching the rejected value in the chained `catch` method on the `runPromises` invocation to catch any errors within the `runPromises` function. Only `"Third"` gets logged, since `promise3` is rejected with this value.

</p>
</details>

---

###### 153. مقدار `method` باید چه باشد تا `{ name: "Lydia", age: 22 }` را لاگ کند؟

```javascript
const keys = ['name', 'age'];
const values = ['Lydia', 22];

const method =
  /* ؟؟ */
  Object[method](
    keys.map((_, i) => {
      return [keys[i], values[i]];
    })
  ); // { name: "Lydia", age: 22 }
```

- الف: `entries`
- ب: `values`
- ج: `fromEntries`
- د: `forEach`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The `fromEntries` method turns a 2d array into an object. The first element in each subarray will be the key, and the second element in each subarray will be the value. In this case, we’re mapping over the `keys` array, which returns an array that the first element is the item on the key array on the current index, and the second element is the item of the values array on the current index.

This creates an array of subarrays containing the correct keys and values, which results in `{ name: "Lydia", age: 22 }`

</p>
</details>

---

###### 154. خروجی این کد چیست؟

```javascript
const createMember = ({ email, address = {} }) => {
  const validEmail = /.+\@.+\..+/.test(email);
  if (!validEmail) throw new Error('Valid email pls');

  return {
    email,
    address: address ؟ address : null,
  };
};

const member = createMember({ email: 'my@email.com' });
console.log(member);
```

- الف: `{ email: "my@email.com", address: null }`
- ب: `{ email: "my@email.com" }`
- ج: `{ email: "my@email.com", address: {} }`
- د: `{ email: "my@email.com", address: undefined }`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ج

The default value of `address` is an empty object `{}`. When we set the variable `member` equal to the object returned by the `createMember` function, we didn't pass a value for the address, which means that the value of the address is the default empty object `{}`. An empty object is a truthy value, which means that the condition of the `address ؟ address : null` conditional returns `true`. The value of the address is the empty object `{}`.

</p>
</details>

---

###### 155. خروجی این کد چیست؟

```javascript
let randomValue = { name: 'Lydia' };
randomValue = 23;

if (!typeof randomValue === 'string') {
  console.log("It's not a string!");
} else {
  console.log("Yay it's a string!");
}
```

- الف: `It's not a string!`
- ب: `Yay it's a string!`
- ج: `TypeError`
- د: `undefined`

<details dir="rtl" align="right"><summary><b>پاسخ</b></summary>
<p>

#### پاسخ: ب

The condition within the `if` statement checks whether the value of `!typeof randomValue` is equal to `"string"`. The `!` operator converts the value to a boolean value. If the value is truthy, the returned value will be `false`, if the value is falsy, the returned value will be `true`. In this case, the returned value of `typeof randomValue` is the truthy value `"number"`, meaning that the value of `!typeof randomValue` is the boolean value `false`.

`!typeof randomValue === "string"` always returns false, since we're actually checking `false === "string"`. Since the condition returned `false`, the code block of the `else` statement gets run, and `Yay it's a string!` gets logged.

</p>
</details>
