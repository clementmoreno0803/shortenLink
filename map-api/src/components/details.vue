<template>
  <div class="title_details">
    <h4>Advanced Statistics</h4>
    <h3 style="margin-bottom: 100px">
      Track how your links are performing across the web with our davanced
      statistics dashboard.
    </h3>
  </div>
  <div class="details_card">
    <div class="card">
      <div class="card_icon" id="brand"></div>
      <div class="cards_description">
        <h4>Brand Recognition</h4>
        <h5>
          Boost vour brand recognition with each click. Generic links dont mean
          a thing. branded links neip Instil conidence in vour content.
        </h5>
      </div>
    </div>
    <div class="card" id="deux">
      <div class="card_icon" id="records"></div>
      <div class="cards_description">
        <h4>Detailed Records</h4>
        <h5>
          Gain insights into who is clicking vour links. Knowing when and where
          peopie engage with your content helps inform better decisions.
        </h5>
      </div>
    </div>
    <div class="card" id="trois">
      <div class="card_icon" id="customize"></div>
      <div class="cards_description">
        <h4>Fully Customizable</h4>
        <h5>
          Improve brand awareness and content discoverability through
          customizable links. supercharging audience engagement.
        </h5>
      </div>
    </div>
    <div id="green_string"></div>
  </div>
</template>

<script>
export default {
  name: "detail",
};
</script>

<style>
.title_details {
  margin: 0 auto;
  text-align: center;
  width: 45%;
}
.details_card {
  display: flex;
  align-items: center;
  justify-content: center;
}
.card {
  width: 25vw;
  height: 250px;
  background: var(--secondary);
  position: relative;
  display: flex;
  justify-content: center;
  margin: 0px 15px 50px 15px;
  border-radius: 5px;
  z-index: 2;
}
.card_icon {
  position: absolute;
  top: -50px;
  left: 25px;
}
#brand {
  background: url("../assets/icon-brand-recognition.svg") hsl(260, 8%, 14%);
  width: 70px;
  height: 70px;
  background-size: 40px;
  padding: 10px;
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 50%;
}
#records {
  background: url("../assets/icon-detailed-records.svg") hsl(260, 8%, 14%);
  width: 70px;
  height: 70px;
  background-size: 40px;
  padding: 10px;
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 50%;
}
#customize {
  background: url("../assets/icon-fully-customizable.svg") hsl(260, 8%, 14%);
  width: 70px;
  height: 70px;
  background-size: 40px;
  padding: 10px;
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 50%;
}
.cards_description {
  width: 83%;
  display: flex;
  flex-direction: column;
  padding: 80px 10px;
}
#green_string {
  height: 10px;
  width: 50%;
  background: var(--primary);
  position: absolute;
  z-index: 1;
}
#deux {
  position: relative;
  top: 40px;
}
#trois {
  position: relative;
  top: 80px;
  margin-bottom: 50px;
}

</style>
