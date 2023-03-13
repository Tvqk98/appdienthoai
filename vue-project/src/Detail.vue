<template>
    <Page>
        <ActionBar flat="true">
          <StackLayout orientation="horizontal">
            <Image src="res://icon" width="40" height="40" verticalAlignment="center" @tap="$navigateBack(App)"/>
            <Label text="Login" fontSize="24" verticalAlignment="center" />
          </StackLayout>
        </ActionBar>
      <Label text="hello" />
        
    </Page>
</template>

<script >
 import App from "./App";
  export default {
    data() {
      return {   

      }
    }
  }
</script>

<style scoped>
    ActionBar {
        background-color: #53ba82;
        color: #ffffff;
    }

    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #333333;
    }
</style>
