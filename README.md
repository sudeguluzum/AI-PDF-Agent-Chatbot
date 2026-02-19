# AI-PDF-Agent-Chatbot
A low-code automation system built with n8n and Google Gemini or Chat GPT that analyzes PDF documents, generates summaries, creates interactive quizzes, and logs scores to Google Sheets.

# AI PDF Agent Chatbot 🤖📄

Bu proje, **n8n** üzerinde çalışan ve **Google Gemini AI** ve **Chat GPT** modelini kullanarak PDF belgeleriyle etkileşime girmeyi sağlayan gelişmiş bir otomasyon akışıdır. Kullanıcılar PDF yükleyebilir, içerik hakkında soru sorabilir ve doküman içeriğinden oluşturulan quizler ile kendilerini test edebilirler.



## ✨ Özellikler / Features

### 🇹🇷 Türkçe
- **PDF Metin Çıkarımı:** Yüklenen PDF dosyalarındaki metinler `Extract From File` düğümü ile otomatik olarak ayıklanır.
- **Yapay Zeka Sohbeti:** Gemini ve Chat GPT AI, doküman içeriğine dayanarak kullanıcı sorularını yanıtlar.
- **Otomatik Quiz Oluşturma:** Doküman içeriğinden 5 soruluk çoktan seçmeli quizler üretir.
- **Akıllı Puanlama:** Kullanıcı cevaplarını analiz eder, puanı hesaplar ve geri bildirim verir.
- **Google Sheets Entegrasyonu:** Quiz sonuçlarını (ID, PDF adı, puan, tarih) otomatik olarak bir tabloya kaydeder.

### 🇺🇸 English
- **PDF Text Extraction:** Automatically extracts text from uploaded PDF files using the `Extract From File` node.
- **AI-Powered Chat:** Gemini AI answers user questions based strictly on the document content.
- **Automatic Quiz Generation:** Generates 5-question multiple-choice quizzes from the content.
- **Smart Scoring:** Analyzes user answers, calculates scores, and provides feedback.
- **Google Sheets Integration:** Automatically logs quiz results (ID, PDF name, score, date) into a spreadsheet.

## 🛠️ Teknolojiler / Tech Stack

- **n8n:** İş akışı otomasyonu (Workflow automation)
- **Google Gemini ve Chat GPT:** Yapay zeka modeli (LLM)
- **LangChain:** AI Agent ve hafıza yönetimi (AI Agent & Memory management)
- **Google Sheets API:** Veri kaydı (Data logging)
- **JavaScript:** Quiz değerlendirme ve veri işleme (Quiz evaluation & data processing via Code Node)

## 🚀 Kurulum / Setup

1. `PDFAgent.json` dosyasını indirin ve n8n arayüzüne **"Import from JSON"** diyerek yükleyin.
2. **Google Gemini API** ya da **Chat GPT API** anahtarınızı `Chat Model` düğümüne ekleyin.
3. **Google Sheets** düğümü için kendi kimlik bilgilerinizi ve hedef tablo ID'nizi yapılandırın.
4. Webhook düğümünü aktif hale getirerek istekleri karşılamaya başlayın.

---
*Bu proje bir ödev kapsamında geliştirilmiştir. / This project was developed as part of an academic assignment.*
