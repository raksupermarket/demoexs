---
title: Complete Demo Post - All Widgets Showcase
date:
  '0': '2'
  '1': '0'
  '2': '2'
  '3': '6'
  '4': '-'
  '5': '0'
  '6': '5'
  '7': '-'
  '8': '0'
  '9': '9'
author: CMS Team
author_email: team@example.com
author_url: https://example.com
draft: false
featured: true
featured_image: /public/images/dbs.png
featured_video: https://youtube.com/watch?v=demo
pinned: true
sticky: true
priority: 1
rating: 4.8
views: 12500
reading_time: 8
categories:
  - Tutorial
  - Showcase
  - Documentation
tags:
  - cms
  - lit-element
  - web-components
seo:
  description: Postingan ini mendemonstrasikan setiap widget yang tersedia di CMS.
  keywords: cms, demo, widgets, headless, lit
  robots: index,follow
  canonical: https://example.com/blog/complete-demo
  og_image: /images/og-demo.jpg
  og_type: article
  twitter_card: summary_large_image
call_to_action:
  enabled: true
  title: Siap untuk Memulai?
  subtitle: Coba headless CMS kami sekarang
  button_text: Mulai Uji Coba Gratis
  button_url: https://example.com/signup
  button_style: primary
  background_color: '#3b82f6'
  text_color: '#ffffff'
---

# Complete Demo: All Widgets Showcase

Isi konten utama di sini...

Ini adalah area konten utama. Di bawah ini adalah visualisasi bagaimana widget-widget di atas dipetakan ke dalam tampilan:

## String Widget
**Judul Postingan:** {{title}}
**Nama Penulis:** {{author}}

## SEO Object Widget
*Widget ini digunakan untuk metadata (tidak perlu menampilkan judul lagi di sini).*
- **Deskripsi:** {{seo.description}}
- **Kata Kunci:** {{seo.keywords}}

## Status Boolean
- **Unggulan:** {{featured}}
- **Disematkan:** {{pinned}}

## Statistik Angka
- **Dilihat:** {{views}}
- **Rating:** {{rating}}/5

## Data Daftar (List)
**Kategori:**
{{#each categories}}
- {{this}}
{{/each}}
