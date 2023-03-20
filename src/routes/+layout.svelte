<script lang='ts'>
  import Footer from '../components/Footer.svelte'
  import Header from '../components/Header.svelte'
  import { base } from '$app/paths'
  import '../styles.css'
</script>

<Header />
<nav>
  <div><a href='{base}/about'>More about me</a></div>
  <a href='{base}/'>Home page</a>
</nav>
<slot />
<Footer />
