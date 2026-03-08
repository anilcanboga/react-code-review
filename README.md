# AI React Code Review Prompt

Bu repository, React kodlarını **AI kullanarak code review yapmak** için hazırlanmış bir **prompt şablonu** içerir.

Prompt; ChatGPT, Claude gibi AI araçlarının bir **Senior React Developer gibi davranarak** React component’lerini incelemesini ve iyileştirme önerileri sunmasını sağlar.

## Amaç

Birçok React uygulaması **çalışır**, ancak kodu her zaman **temiz, sürdürülebilir ve ölçeklenebilir** şekilde yazılmış olmaz.

Bu prompt, özellikle junior developer’ların React kodlarında sık görülen pattern’leri tespit eder ve **React best practice’lerine uygun iyileştirmeler** önerir.

## Prompt Neleri İnceler?

AI review sürecinde aşağıdaki alanlara odaklanır:

* **Naming convention**
* **JSX tekrarları ve `.map()` kullanımı**
* **Kod organizasyonu**
* **Custom hook çıkarma fırsatları**
* **Reusable component önerileri**
* **Semantic HTML kullanımı**
* **Accessibility iyileştirmeleri**
* **Proje dosya yapısı**
* **TypeScript best practices**
* **React best practices**
* **Styling best practices**

Her tespit edilen problem için AI şu formatta geri bildirim verir:

```id="jsk29s"
❌ You did this:
[Orijinal kod]

✅ After review, this is correct:
[Geliştirilmiş kod]

💡 Explanation:
[Bu değişikliğin neden daha iyi olduğuna dair açıklama]
```

## Nasıl Kullanılır?

1. Bu repository’deki **React Code Review Prompt**’u kopyalayın.
2. ChatGPT veya Claude gibi bir AI aracına yapıştırın.
3. Prompt’un altına React component kodunuzu ekleyin.
4. Mesajı gönderin.

AI, kodunuzu analiz ederek **iyileştirme önerileri ve geliştirilmiş örnek kodlar** sunacaktır.

## Faydaları

Bu prompt’u düzenli kullanmak geliştiricilere şu konularda yardımcı olur:

* **Kod kalitesini artırmak**
* **React best practice’lerini öğrenmek**
* **Daha temiz ve sürdürülebilir component’ler yazmak**
* **Junior seviyesinde görülen kod pattern’lerini fark etmek**

## Özelleştirme

Prompt’u ihtiyacınıza göre genişletebilirsiniz. Örneğin:

* Error handling kontrolü
* Performance optimization önerileri
* Responsive design kontrolleri

### ENGLISH

# AI React Code Review Prompt

This repository contains a **prompt template** that helps developers review React code using AI tools like ChatGPT or Claude.

The prompt acts like a **Senior React Developer performing a code review**. It analyzes React components and provides structured feedback with improved code examples.

## Purpose

Many React applications work correctly but are not written in a **clean, scalable, and maintainable way**.
This prompt helps identify common issues found in junior-level React code and suggests improvements based on **React best practices**.

## What the Prompt Reviews

The AI review focuses on the following areas:

* **Naming conventions**
* **JSX repetition and `.map()` usage**
* **Code organization**
* **Custom hook extraction**
* **Reusable component opportunities**
* **HTML semantic tags**
* **Accessibility improvements**
* **Project structure**
* **TypeScript best practices**
* **React best practices**
* **Styling best practices**

For every issue found, the AI returns feedback in a structured format:

```
❌ You did this:
[Original code]

✅ After review, this is correct:
[Improved code]

💡 Explanation:
[Why the change improves the code]
```

## How to Use

1. Copy the **React Code Review Prompt** from this repository.
2. Paste it into an AI tool (ChatGPT, Claude, etc.).
3. Add your React component below the prompt.
4. Send the message.

The AI will analyze the code and return **actionable feedback and improved examples**.

## Benefits

Using this prompt regularly helps developers:

* Improve **code quality**
* Learn **React best practices**
* Write **cleaner and more maintainable components**
* Identify **junior-level coding patterns**

## Customization

You can customize the prompt by adding extra review rules, such as:

* Error handling checks
* Performance optimization suggestions
* Responsive design validation

