# دليل التثبيت — Project Z

> الدليل ده هيتحدث مع كل مرحلة.

## المتطلبات حالياً (مرحلة التخطيط)

### أجهزة موصى بها
- **ممتاز**: RTX 4090 / 5090 أو ما يعادلها (24GB+ VRAM)
- **جيد**: RTX 3090 / 4080 (16–24GB)
- **مقبول**: أي جهاز فيه 32GB RAM + موديل 14B quantized

### البرامج
1. [Ollama](https://ollama.com) — أحدث نسخة
2. Python 3.11 أو أحدث
3. Node.js 20+
4. Git

### الموديلات المقترحة
```bash
# الأفضل حالياً للكود
ollama pull qwen2.5-coder:32b

# بديل قوي
ollama pull deepseek-coder-v2

# لو الجهاز ضعيف
ollama pull qwen2.5-coder:14b
```

---

سيتم إضافة أوامر التثبيت الكاملة (`pip install` و`npm install`) عند جاهزية النواة.
