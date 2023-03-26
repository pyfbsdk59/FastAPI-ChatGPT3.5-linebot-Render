# FastAPI-ChatGPT3.5-linebot-Render
# 一個使用FastAPI框架和GPT3.5 turbo模型官方API，創造一個linebot，快速建置於平台Render。


## [TelegramBot Vercel GPT3.5 turbo/ChatGPT版本部署](https://github.com/pyfbsdk59/Flask-official-ChatGPT-TelegramBot-Vercel)

<div align="center">
  <img src="demo/demo_351.png" width="500"/>
</div>


## [TelegramBot Render GPT3版本部署](https://github.com/pyfbsdk59/Flask-ChatGPT-TelegramBot-Render)

<div align="center">
  <img src="demo/link.png" width="700"/>
</div>

## [LineBot Django Vercel GPT3版本部署](https://github.com/pyfbsdk59/Django-ChatGPT-linebot-Vercel)

<div align="center">
  <img src="demo/link2.png" width="700"/>
</div>

## [TelegramBot Golang Render GPT3版本部署](https://github.com/pyfbsdk59/Golang-ChatGPT-TelegramBot-Render)

<div align="center">
  <img src="demo/link3.png" width="700"/>
</div>

<div align="center">
  <img src="demo/link3a.png" width="600"/>
</div>

## [LineBot Golang Render GPT3版本部署](https://github.com/pyfbsdk59/Golang-ChatGPT-linebot-Render)

<div align="center">
  <img src="demo/link4.png" width="700"/>
</div>




#### GPT3 TelegramBot Vercel部署版本。程式猿影音教學參考。請支持且訂閱加按讚感謝他的辛勞。

https://www.youtube.com/watch?v=eKKEa6NhCd0

<div align="center">
  <img src="demo/demo0.png" width="800"/>
</div>

### [English](https://github.com/pyfbsdk59/FastAPI-GPT3.5-linebot-Render/blob/main/README_en.md)
### [日本語](https://github.com/pyfbsdk59/FastAPI-GPT3.5-linebot-Render/blob/main/README_jp.md)


### 1. 本專案參考了以下前輩和官方的方案改成製作，只針對剛學習Python或FastAPI的朋友來佈置linebot在Render上。Render可取代取消免費方案的Heroku，來測試Side Project。

https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel


#### 2. 本專案因部屬在Render上，所以專案結構和Vercel或Railway版本些許不同。Render網站中，選擇新增「Web Services」，可用github帳號匯入此專案，可先fork到自己的帳號，然後設定自己的名稱和選擇免費free方案。記得按下方「Advanced」，設定環境變數。


<div align="center">
  <img src="demo/render1.png" width="600"/>
</div>

<div align="center">
  <img src="demo/render2.png" width="700"/>
</div>

#### 3. 必須在Render的Environment Variables設定3個環境變數，分別是OPENAI_API_KEY和LINE_CHANNEL_SECRET和LINE_CHANNEL_ACCESS_TOKEN。然後開始部屬，可能要花上一些時間。成功後複製自己的URL貼到line developer的Webhook URL來做設定和測試。例如：

https://xxx.onrender.com/

<div align="center">
  <img src="demo/render3.png" width="700"/>
</div>



### 4. 和Vercel版本的差別，注意Start Command要改為gunicorn config.wsgi:application來啟動。（一個坑，可以省你很多時間）

<div align="center">
  <img src="demo/render_uvicorn.png" width="600"/>
</div>

------
### Line和openai api設置請參考： https://github.com/howarder3/GPT-Linebot-python-flask-on-vercel