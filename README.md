# 🎈 Streamlit App 

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/streamlit/llm-examples?quickstart=1)

ตัวอย่างเริ่มต้นสำหรับการสร้างแอป LLM ด้วย Streamlit.

## Overview of the App

แอปนี้นำเสนอคอลเลกชันตัวอย่างการทำงานขั้นต่ำของ LLM ที่เพิ่มมากขึ้น.

ตัวอย่างปัจจุบันได้แก่:

- แชทบอท
- ไฟล์ถามตอบ
- สนทนาด้วยการค้นหาทางอินเทอร์เน็ต
- การเริ่มต้นอย่างรวดเร็วของ LangChain
- เทมเพลตพรอมต์ LangChain
- สนทนากับความคิดเห็นของผู้ใช้

## Demo App


### Get an OpenAI `API key` = คือ อะไร หาได้ที่ไหน ` น้องมิ้น `มีคำตอบ

คุณพี่สามารถรับคีย์ OpenAI API ของคุณเองได้โดยทำตามคำแนะนำต่อไปนี้:

1. ไปที่ https://platform.openai.com/account/api-keys.
2.  คลิกที่ `+ Create new secret key` button.
3. จากนั้นป้อนชื่อตัวระบุ (ไม่บังคับ) แล้วคลิกที่`Create secret key` button.

### ป้อนคีย์ OpenAI API ใน Streamlit Community Cloud

หากต้องการตั้งค่าคีย์ OpenAI API เป็นตัวแปรสภาพแวดล้อมในแอป Streamlit ให้ทำดังต่อไปนี้:

ที่มุมขวาล่าง ให้คลิกที่จาก`< Manage app`นั้นคลิกที่แนวตั้ง "..." ตามด้วยการคลิกที่`Settings`
สิ่งนี้จะนำการตั้งค่าแอพมาคลิกถัดไปบน`Secrets`แท็บและวางคีย์ API ลงในกล่องข้อความดังนี้:

```sh
OPENAI_API_KEY='xxxxxxxxxx'
```

## Run it locally หรือ รันข้อมูลบนเครื่องของคุณพี่

```sh
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run Chatbot.py
```
