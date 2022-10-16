<script>
  export let image;
  export let alt;
</script>

<div class="flip-card bg-transparent ">
    <div class="flip-card-inner">
        <div class="flip-card-front">
            <img type="image/webp" alt={alt} srcset={image}/>
        </div>
        <div class="flip-card-back grid pr-8 pl-8 place-content-center">
            <slot>
            </slot>
          </div>
    </div>
</div>

<style>
    .flip-card {
    background-color: transparent;
    perspective: 1000px; /* Remove this if you don't want the 3D effect */
  }
  
  /* This container is needed to position the front and back side */
  .flip-card-inner {
    position: relative;
    width: 100%;
    height: 100%;
    text-align: center;
    transition: transform 0.8s;
    transform-style: preserve-3d;
  }
  
  /* Do an horizontal flip when you move the mouse over the flip box container */
  .flip-card:hover .flip-card-inner {
    transform: rotateY(180deg);
  }

  
  
  /* Position the front and back side */
  .flip-card-front {
    width: 100%;
    height: 100%;
    -webkit-backface-visibility: hidden; /* Safari */
    backface-visibility: hidden;
  }


  /* Position the front and back side */
  .flip-card-back {
    position: absolute;
    top: 0;
    width: 100%;
    height: 100%;
    -webkit-backface-visibility: hidden; /* Safari */
    backface-visibility: hidden;
  }

  
  
  .flip-card-back {
    background-color: var(--bgcolor);    
    transform: rotateY(180deg);
  }
</style>