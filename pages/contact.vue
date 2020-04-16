<template>
  <div class="contents">
    <h2 class="title">CONTACT</h2>
    <div class="contact-main">
      <div class="contact-message">
        ご連絡は以下のフォームからお願い致します。
      </div>
      <div class="contact-form"> 
        <form name="contact" method="post" data-netlify="true">
          <input type="hidden" name="form-name" value="contact" />
          <p>
            <label>Name<input type="text" name="name" required="required" /></label>   
          </p>
          <p>
            <label>Email<input type="email" name="email" required="required"/></label>
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