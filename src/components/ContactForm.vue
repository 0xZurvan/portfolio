<template>
  <div class="form-container">
    <form action="" method="GET">
      <label>
        First name:
        <input type="text" name="first_name" maxlength="30" placeholder="type here..."/>
      </label>
      <br />
      <label>
        Email:
        <input type="email" name="email" required="required" placeholder="type here..."/>
      </label>
      <br />
        <textarea cols="32" rows="5">Write your message...</textarea>
      <br />
      <input type="submit" value="send" />
    </form>
  </div>
</template>
