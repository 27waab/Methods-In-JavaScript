# String-Methods-In-JavaScript
| الاسم | ماذا يفعل؟ | مثال مختصر |
|------|----------|-------------|
| **length** | يرجّع طول النص (خاصية مو دالة). | `"abc".length // 3` |
| **charAt()** | يرجع الحرف الموجود في index معيّن. | `"hi".charAt(1) // 'i'"` |
| **charCodeAt()** | يرجّع كود Unicode للحرف. | `"A".charCodeAt(0)"` |
| **at()** | يرجّع الحرف ويدعم index السالب. | `"abc".at(-1) // 'c'"` |
| **slice()** | يرجّع جزء من النص. | `"hello".slice(1,4) // 'ell'"` |
| **substring()** | يعيد جزء من النص (بدون أرقام سالبة). | `"hello".substring(1,4)"` |
| **substr()** | قديم — يقتطع من index بطول محدد. | `"hello".substr(1,3)"` |
| **toUpperCase()** | يحول النص لكابيتال. | `"hi".toUpperCase()"` |
| **toLowerCase()** | يحوله لسمول. | `"HI".toLowerCase()"` |
| **trim()** | يشيل المسافات من البداية والنهاية. | `" hi ".trim()"` |
| **trimStart()** | يشيل المسافات من البداية. | `" hi".trimStart()"` |
| **trimEnd()** | يشيل المسافات من النهاية. | `"hi ".trimEnd()"` |
| **includes()** | يتحقق هل النص يحتوي شيء. | `"hello".includes("ll") // true"` |
| **startsWith()** | يتحقق هل يبدأ بـ. | `"hello".startsWith("he")"` |
| **endsWith()** | يتحقق هل ينتهي بـ. | `"hello".endsWith("lo")"` |
| **indexOf()** | أول موقع لوجود كلمة. | `"hello".indexOf("l") // 2"` |
| **lastIndexOf()** | آخر موقع لوجود كلمة. | `"hello".lastIndexOf("l") // 3"` |
| **repeat()** | يكرر النص. | `"ha".repeat(3) // 'hahaha'"` |
| **replace()** | يستبدل أول تطابق. | `"hi hi".replace("hi","yo")"` |
| **replaceAll()** | يستبدل كل التطابقات. | `"hi hi".replaceAll("hi","yo")"` |
| **match()** | يرجّع نتائج regex. | `"a1b2".match(/\\d+/g)"` |
| **matchAll()** | يرجّع كل تطابقات regex. | `[... "a1b2".matchAll(/\\d/g)]` |
| **search()** | يدور بـ regex ويعطي أول index. | `"a1b2".search(/\\d/)"` |
| **split()** | يقسّم النص لمصفوفة. | `"a,b,c".split(",")"` |
| **padStart()** | يعبّي بداية النص لطول معيّن. | `"5".padStart(3, "0") // '005'"` |
| **padEnd()** | يعبّي نهاية النص. | `"5".padEnd(3, "0") // '500'"` |
| **concat()** | يجمع نصوص (نادر الاستخدام). | `"a".concat("b")"` |
| **localeCompare()** | يقارن نصين للفرز. | `"a".localeCompare("b")"` |
| **normalize()** | يوحّد شكل Unicode. | `"é".normalize()"` |
| **toString()** | يرجّع النص (غير مهم غالبًا). | `"abc".toString()"` |
| **valueOf()** | يرجّع القيمة الأولية للنص. | `"abc".valueOf()"` |
