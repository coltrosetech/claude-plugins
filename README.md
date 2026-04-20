# coltrosetech/claude-plugins

[Coltrose Tech](https://github.com/coltrosetech)'in Claude Code plugin marketplace'i. Şimdilik tek plugin, ama genişleyecek.

## Kullan

Claude Code içinde:

```
/plugin marketplace add coltrosetech/claude-plugins
/plugin install liquid-ios@coltrosetech
```

Sonra Claude Code'u yeniden başlat. Bittin.

## Plugins

### [`liquid-ios`](https://github.com/coltrosetech/liquid-ios)

Design-DNA-first iOS app geliştirme akışı. SwiftUI yazmadan önce 3 interaktif HTML tasarım DNA prototipi üretir, seçtiğin DNA'yı kalıcı `.design/` sistemine kilitler, sonra motion-fidelity kurallarına uygun SwiftUI çıktısı verir.

- Router skill + init + feature + tweak
- 3 varsayılan DNA: Liquid Native · Editorial Crisp · Playful Character
- Motion-fidelity whitelist (CSS ↔ SwiftUI 1:1 eşleşme)
- Superpowers kompozisyonu (brainstorming, verification, simplify)

**Örnek projeler:** [coltrosetech/liquid-ios-examples](https://github.com/coltrosetech/liquid-ios-examples) — 3 çalışan demo app (Todo, Breathe, Sprout).

## Katkıda bulunmak

Bu marketplace Coltrose Tech'in kendi plugin'leri için. Kendi plugin'ini duyurmak istiyorsan kendi marketplace repo'nu aç — yapı çok basit:

```
your-marketplace/
└── .claude-plugin/
    └── marketplace.json    # { name, plugins: [{ name, source: { url } }] }
```

Detay: [Claude Code plugins documentation](https://docs.claude.com/en/docs/claude-code/plugins).

## Lisans

MIT — marketplace'in kendisi. Her plugin kendi lisansını taşır (liquid-ios MIT'tir).
