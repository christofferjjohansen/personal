<template>
  <div class="home-page">
    <div class="title-container">
      <h1 class="heading-1">christoffer johansen</h1>
    
      <div class="sub-container">
        <p class="subtitle-2">
          senior software developer @ <a href="https://wizebank.co" target="_blank" rel="noopener noreferrer">wizebank</a>
        </p>

        <p class="subtitle-2">
          founder @ <a href="https://treefort.io" target="_blank" rel="noopener noreferrer">treefort</a>
        </p>

        <div class="social-links">
          <a href="https://linkedin.com/in/christofferjjohansen/" target="_blank" rel="noopener noreferrer">linkedIn</a>
          <a href="https://github.com/christofferjjohansen" target="_blank" rel="noopener noreferrer">github</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .home-page {
    width: 100%;
    height: 100%;

    display: flex;
    justify-content: center;
    align-items: center;

    .title-container {
      padding: 3rem 2rem;
      border-radius: 11px;
    }

    .sub-container {
      padding: .5rem;
    }

    .social-links {
      padding: .5rem 0;

      a {
        margin-right: .5rem;
      }
    }
  }
</style>
