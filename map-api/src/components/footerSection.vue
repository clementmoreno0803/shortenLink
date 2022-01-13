<template>
  <div class="footer">
    <img src="../assets/logo.svg" alt="" id="white_logo" />
    <table>
      <thead>
        <tr>
          <th class="tg-0lax">Features</th>
          <th class="tg-0lax">Ressources</th>
          <th class="tg-0lax">Company</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="tg-0">Link Shortening</td>
          <td class="tg-0">Blog</td>
          <td class="tg-0">About</td>
        </tr>
        <tr>
          <td class="tg-0">Branded Links</td>
          <td class="tg-0">Developous</td>
          <td class="tg-0">Our Team</td>
        </tr>
        <tr>
          <td class="tg-0">Analytics</td>
          <td class="tg-0">Support</td>
          <td class="tg-0">Careers</td>
        </tr>
        <tr>
          <td class="tg-0"></td>
          <td class="tg-0"></td>
          <td class="tg-0">Contact</td>
        </tr>
      </tbody>
    </table>
    <ul>
      <li class="network_icon fa-brands fa-facebook-square" ><a href="#"></a></li>
      <li class="network_icon fa-brands fa-twitter"><a href="#"></a></li>
      <li class="network_icon fa-brands fa-pinterest"><a href="#"></a></li>
      <li class="network_icon fa-brands fa-instagram"><a href="#"></a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "footerSection",
};
</script>

<style>
.footer {
  position: relative;
  top: 100px;
  height: 200px;
  width: 100%;
  background: var(--footer);
  display: flex;
  justify-content: space-around;
  align-items: flex-start;
  padding : 50px 0;
}
#white_logo {
  filter: invert(100%) sepia(100%) saturate(2%) hue-rotate(238deg)
    brightness(109%) contrast(101%);
}
.tg-0lax{
  font-family: 'Poppins';
  color: white;
  text-align: left;
}
.tg-0{
  font-family: 'Poppins';
  color: white;
  opacity: 0.4;
  font-weight: 500;
  padding-right: 90px;
}
.tg-0:hover{
  color: var(--primary);
  opacity: 1;
  transition: all 0.4s ease;
}
.network_icon{
  color: var(--secondary);
  font-size: 2rem;
}
.fa-brands:hover{
  color: var(--primary);
  transition: all 0.4s ease;
}
</style>
