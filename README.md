# Softbreak-AI

Softbreak-AI, **LobeChat** tabanlı modern bir yapay zeka sohbet uygulaması geliştirme platformudur. Bu proje, kullanıcılar için özelleştirilebilir bir yapay zeka sohbet deneyimi sunmayı amaçlar ve Softbreak topluluğunun ihtiyaçlarına göre optimize edilmiştir.

## 🚀 Özellikler

- **Dosya Yükleme ve Bilgi Tabanı**  
  Kullanıcılar çeşitli dosyalar (belgeler, görseller, ses ve video) yükleyebilir ve bilgi tabanları oluşturabilir.

- **Çoklu Model Desteği**  
  AWS Bedrock, OpenAI, Anthropic (Claude), Google AI gibi birden fazla model sağlayıcısını destekler.

- **Yerel Model Kullanımı**  
  Ollama gibi yerel modellerle çalışma imkanı sunar.

- **Görsel Tanıma**  
  GPT-4-vision modelini destekler, görselleri analiz edebilir ve sohbet sırasında bunları kullanabilir.

- **Sesli İletişim**  
  Metin-ses (TTS) ve ses-metin (STT) teknolojileriyle gerçekçi bir iletişim deneyimi sağlar.

- **Metinden Görsel Oluşturma**  
  DALL-E 3, MidJourney ve benzeri araçlarla metinden görsel üretimi.

- **Eklenti Sistemi**  
  Genişletilebilir fonksiyonlar ve özel eklentilerle sohbet deneyimini zenginleştirir.

- **Ajan Pazarı (GPTs)**  
  Özel ajanlar oluşturabilir ve diğer kullanıcılarla paylaşabilirsiniz.

- **PWA Desteği**  
  Progressive Web Application (PWA) teknolojisiyle hem masaüstü hem de mobil cihazlarda optimize edilmiş bir deneyim.

## 📦 Dağıtım

### Docker ile Dağıtım

Softbreak-AI'yi Docker kullanarak dağıtmak için aşağıdaki adımları izleyin:

```bash
docker run -d -p 3210:3210 \
  -e OPENAI_API_KEY=sk-xxxx \
  -e ACCESS_CODE=softbreak123 \
  --name softbreak-ai \
  lobehub/lobe-chat
