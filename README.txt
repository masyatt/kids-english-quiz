Kids English Quiz — Quick Deploy

Files:
- index.html  : Full version (PC/Mobile, settings included)
- embed.html  : Embed-friendly version (for Tistory, etc.)
- thumbnail.png: Blog thumbnail (1200x630)

GitHub Pages Deploy:
1) Create a public repo on GitHub (e.g., kids-english-quiz)
2) Upload index.html, embed.html, thumbnail.png to the repo root
3) Settings → Pages → Source: Deploy from a branch, Branch: main (root)
4) After it builds, your site will be at: https://<USER>.github.io/kids-english-quiz/

Tistory (iframe):
<iframe src="https://<USER>.github.io/kids-english-quiz/embed.html" width="100%" height="680"
        style="border:0;border-radius:12px;overflow:hidden" allow="autoplay" loading="lazy"></iframe>

Naver Blog (button link):
<div style="text-align:center;margin:18px 0;">
  <a href="https://<USER>.github.io/kids-english-quiz/index.html" target="_blank"
     style="display:inline-block;padding:14px 20px;background:#111827;color:#fff;border-radius:10px;text-decoration:none;font-weight:700;">
    👶 유아용 영어 단어 게임 시작하기
  </a>
  <div style="font-size:12px;color:#6b7280;margin-top:8px;">(새 창에서 실행 · TTS 지원)</div>
</div>
