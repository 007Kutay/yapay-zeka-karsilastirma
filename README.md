# Yapay Zeka Araçları Karşılaştırması

Bu repo, farklı yapay zeka araçlarının **metin** ve **görsel üretim** yeteneklerini karşılaştıran bir çalışmanın belgesidir.

---

## Karşılaştırılan Araçlar

| Araç | Metin Üretimi | Görsel Üretimi |
|------|:---:|:---:|
| Gemini (Google) | ✅ | ✅ |
| ChatGPT (OpenAI) | ✅ | ✅ |
| Claude (Anthropic) | ✅ | ❌ |
| Microsoft Copilot | ✅ | ✅ |
| DeepSeek | ✅ | ❌ |

---

## Metin Üretimi

> **Görev:** [prompt.md](./metin-uretimi/prompt.md) &nbsp;|&nbsp; **Detaylı Karşılaştırma:** [karsilastirma.md](./metin-uretimi/karsilastirma.md)

| Kriter | Gemini | ChatGPT | Claude | Copilot | DeepSeek |
|--------|:------:|:-------:|:------:|:-------:|:--------:|
| Doğruluk | 8/10 | 9/10 | 9/10 | 9/10 | 9/10 |
| Süre | 10/10 | 10/10 | 10/10 | 10/10 | 10/10 |
| Maliyet | — | — | — | — | — |
| Biçime Uyum | 9/10 | 10/10 | 9/10 | 10/10 | 9/10 |

**Kazanan:** ChatGPT ve Microsoft Copilot — Doğruluk: 9/10, Biçime Uyum: 10/10

Çıktılar:
[Gemini](./metin-uretimi/ciktilar/gemini.md) &nbsp;|&nbsp;
[ChatGPT](./metin-uretimi/ciktilar/chatgpt.md) &nbsp;|&nbsp;
[Claude](./metin-uretimi/ciktilar/claude.md) &nbsp;|&nbsp;
[Copilot](./metin-uretimi/ciktilar/copilot.md) &nbsp;|&nbsp;
[DeepSeek](./metin-uretimi/ciktilar/deepseek.md)

---

## Görsel Üretimi

> **Görev:** [prompt.md](./gorsel-uretimi/prompt.md) &nbsp;|&nbsp; **Detaylı Karşılaştırma:** [karsilastirma.md](./gorsel-uretimi/karsilastirma.md)

| Kriter | Gemini | ChatGPT | Copilot |
|--------|:------:|:-------:|:-------:|
| Promota Sadakat | 9/10 | 10/10 | 9/10 |
| Yazı ve Yüzler | 9/10 | 10/10 | 10/10 |
| Tutarlılık | 8/10 | 10/10 | 9/10 |
| Maliyet | 10/10 | 10/10 | 9/10 |

**Kazanan:** ChatGPT — tüm kriterlerde 10/10

### Üretilen Görseller

| Gemini | ChatGPT | Copilot |
|:------:|:-------:|:-------:|
| ![Gemini çıktısı](./gorsel-uretimi/ciktilar/gemini/gemini.jpg) | ![ChatGPT çıktısı](./gorsel-uretimi/ciktilar/chatgpt/chatgpt.png) | ![Copilot çıktısı](./gorsel-uretimi/ciktilar/copilot/copilot.png) |

---

## Araç Analizleri

Her araç için detaylı analiz:
[Gemini](./arac-analizi/gemini.md) &nbsp;|&nbsp;
[ChatGPT](./arac-analizi/chatgpt.md) &nbsp;|&nbsp;
[Claude](./arac-analizi/claude.md) &nbsp;|&nbsp;
[Copilot](./arac-analizi/copilot.md) &nbsp;|&nbsp;
[DeepSeek](./arac-analizi/deepseek.md)

---

## Repo Yapısı

```
yapay-zeka-karsilastirma/
├── metin-uretimi/
│   ├── prompt.md              # Görev tanımı
│   ├── karsilastirma.md       # Skor tablosu
│   └── ciktilar/
│       ├── gemini.md
│       ├── chatgpt.md
│       ├── claude.md
│       ├── copilot.md
│       └── deepseek.md
├── gorsel-uretimi/
│   ├── prompt.md              # Görev tanımı
│   ├── karsilastirma.md       # Skor tablosu + görseller
│   └── ciktilar/
│       ├── gemini/gemini.jpg
│       ├── chatgpt/chatgpt.png
│       └── copilot/copilot.png
└── arac-analizi/
    ├── gemini.md
    ├── chatgpt.md
    ├── claude.md
    ├── copilot.md
    └── deepseek.md
```
