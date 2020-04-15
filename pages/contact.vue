<template>
  <div class="container">
    <h2 class="title">CONTACT</h2>
    <div class="contact-main">
      <div class="contact-message">
        ご連絡は以下のフォームからお願い致します。
      </div>
      <div class="contact-form"> 
        <form name="contact" method="POST" data-netlify="true">
          <p>
            <label>お名前<input type="text" name="name" /></label>   
          </p>
          <p>
            <label>メールアドレス<input type="email" name="email" /></label>
          </p>
          <p>
            <label>メッセージ<textarea name="message"></textarea></label>
          </p>
          <p>
            <button type="submit">送信</button>
          </p>
        </form>
      </div>   
      




    </div>
  </div>
</template>