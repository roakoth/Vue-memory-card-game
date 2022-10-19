<script>
 export default {
  props: {
    onClick: Function,
    
  }
}
</script>

<template>
   <div id="game-over-wrapper">
			<div id="game-over">
				<div>
					<h1>The Game is over !</h1>
				</div>
				<div>
					<h2>You won!</h2>
				</div>
				<div id="play-again-button-container">
					<button id="play-again-button" type="button" @click='onClick()'>Play Again</button>
				</div>
			</div>
		</div>
</template>