<template>
  <push-notification></push-notification>
</template>

<script>
import PushNotification from './components/PushNotification.vue';

export default {
  
  components: { PushNotification }

}
</script>

<style lang="postcss">
:root {

    --white : hsl(0, 0%, 100%);
    
    --gray-97 : hsl(228, 33%, 97%);
    --gray-94 : hsl(223, 21%, 94%);
    --gray-45 : hsl(222, 4%, 40%);
    
    --green-50 : hsl(122, 39%, 50%);
    --red-50 : hsl(0, 100%, 50%);
    
    --black : hsl(180, 7%, 5%);

}

* {
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
}

html {
    height : 100%;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: var(--gray-97);
    height : 100%;
    margin: 0px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 15px;
}

</style>
