<template>
  <div class="portfolio-page">
    <section class="cover-card">
      <div class="cover-dark">
        <span>CREATIVE</span>
        <span>PORTFOLIO</span>
      </div>

      <q-img src="/woman.png" class="cover-image" fit="cover" no-spinner />

      <div class="cover-bottom">
        <div>
          <small>Design by:</small>
          <span>Creative Studio</span>
        </div>

        <span>2023</span>
      </div>
    </section>

    <section class="portfolio-grid">
      <div class="portfolio-card">
        <h3>INDEX</h3>

        <div class="small-list">
          <span>ABOUT THE STUDIO</span>
          <span>MODERN FASHION</span>
          <span>NEW COLLECTION</span>
          <span>INTERIORS</span>
          <span>BEST COLLECTION</span>
        </div>

        <q-img src="/man.png" class="small-image" fit="cover" no-spinner />
      </div>

      <div class="portfolio-card">
        <h3>ABOUT THE STUDIO</h3>

        <p>
          We create modern visual experiences with a clean and timeless
          approach.
        </p>

        <div class="red-shape"></div>
      </div>

      <div class="portfolio-card">
        <h3>TEAM</h3>

        <div class="team-images">
          <q-img src="/woman.png" fit="cover" no-spinner />

          <q-img src="/man.png" fit="cover" no-spinner />
        </div>
      </div>

      <div class="portfolio-card">
        <h3>MISSION - VALUES</h3>

        <p>
          Creativity<br />
          Quality<br />
          Innovation<br />
          Experience
        </p>

        <q-img src="/woman.png" class="value-image" fit="cover" no-spinner />
      </div>

      <div class="portfolio-card">
        <h3>MODERN FASHION</h3>

        <q-img src="/man.png" class="wide-image" fit="cover" no-spinner />

        <p>Modern fashion show</p>
      </div>

      <div class="portfolio-card">
        <h3>MODERN FASHION</h3>

        <div class="fashion-images">
          <q-img src="/man.png" fit="cover" no-spinner />

          <q-img src="/woman.png" fit="cover" no-spinner />
        </div>
      </div>

      <div class="portfolio-card">
        <h3>NEW COLLECTION</h3>

        <div class="collection-layout">
          <q-img src="/man.png" fit="cover" no-spinner />

          <q-img src="/woman.png" fit="cover" no-spinner />
        </div>
      </div>

      <div class="portfolio-card">
        <h3>INTERIORS</h3>

        <div class="interior-images">
          <div></div>
          <div></div>
          <div></div>
        </div>

        <p>Interior collection</p>
      </div>

      <div class="portfolio-card">
        <h3>BEST COLLECTION</h3>

        <div class="best-layout">
          <q-img src="/man.png" fit="cover" no-spinner />

          <div class="best-text">
            <span>01</span>
            <span>02</span>
            <span>03</span>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style lang="sass" scoped>

.portfolio-page
  width: 1055px
  min-height: 653px
  margin: 0 auto
  padding: 25px
  display: flex
  gap: 25px
  background: #e7e4df
  box-sizing: border-box
  overflow: hidden

.cover-card
  width: 38%
  height: 600px
  position: relative
  padding: 12px
  background: #ffffff
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15)
  box-sizing: border-box

.cover-dark
  position: absolute
  top: 12px
  left: 12px
  bottom: 45px
  width: 75px
  z-index: 3
  display: flex
  flex-direction: column
  justify-content: center
  align-items: center
  background: #111111
  color: #ffffff
  writing-mode: vertical-rl
  transform: rotate(180deg)
  gap: 8px
  font-family: Arial, sans-serif
  font-size: 18px
  letter-spacing: 2px

.cover-image
  width: 100%
  height: 535px
  object-fit: cover

.cover-bottom
  height: 40px
  display: flex
  align-items: center
  justify-content: space-between
  padding: 0 8px
  font-family: Arial, sans-serif
  font-size: 8px

.cover-bottom div
  display: flex
  flex-direction: column

.cover-bottom small
  color: #777777
  margin-bottom: 2px

.portfolio-grid
  flex: 1
  display: grid
  grid-template-columns: repeat(3, 1fr)
  grid-template-rows: repeat(3, 1fr)
  gap: 12px

.portfolio-card
  position: relative
  min-height: 185px
  padding: 12px
  background: #ffffff
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08)
  box-sizing: border-box
  overflow: hidden

.portfolio-card h3
  margin: 0 0 12px
  color: #222222
  font-family: Arial, sans-serif
  font-size: 9px
  font-weight: 600
  letter-spacing: 0.4px

.portfolio-card p
  margin: 8px 0
  color: #444444
  font-family: Arial, sans-serif
  font-size: 7px
  line-height: 1.5

.small-list
  width: 55%
  display: flex
  flex-direction: column
  gap: 7px

.small-list span
  padding-bottom: 3px
  border-bottom: 1px solid #dddddd
  color: #555555
  font-size: 6px

.small-image
  position: absolute
  right: 10px
  bottom: 10px
  width: 60px
  height: 85px

.red-shape
  position: absolute
  right: -20px
  bottom: -35px
  width: 130px
  height: 80px
  background: #a92f26
  border-radius: 50% 50% 0 0

.team-images
  display: flex
  gap: 7px

.team-images .q-img
  width: 75px
  height: 90px

.value-image
  position: absolute
  right: 10px
  bottom: 10px
  width: 65px
  height: 80px

.wide-image
  width: 100%
  height: 90px

.fashion-images
  display: flex
  gap: 7px

.fashion-images .q-img
  width: 50%
  height: 105px

.collection-layout
  display: flex
  gap: 6px

.collection-layout .q-img:first-child
  width: 45%
  height: 105px

.collection-layout .q-img:last-child
  width: 55%
  height: 105px

.interior-images
  display: flex
  gap: 6px
  margin-top: 20px

.interior-images div
  flex: 1
  height: 75px
  background: #d8d3cb

.interior-images div:nth-child(2)
  background: #b8b0a5

.interior-images div:nth-child(3)
  background: #eeeae4

.best-layout
  display: flex
  gap: 12px

.best-layout .q-img
  width: 75px
  height: 105px

.best-text
  display: flex
  flex-direction: column
  gap: 12px
  font-size: 8px
  color: #555555
</style>
