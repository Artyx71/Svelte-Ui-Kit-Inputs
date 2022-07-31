<script>
	let showText = 'Заголовок';
	export let hide;
	export let mail;
	export let leftIcon;
	export let rightIcon;
</script>

<main class="input">
	<span class="input__title {hide}">{showText}</span>
	<div class="input__wrap">
		<img class={leftIcon ? 'true' : 'hide'} src={leftIcon} alt="#" />
		<input class="input__enter" type="text" placeholder="Текст" />
		<img class={mail ? 'true' : 'hide'} src={mail} alt="#" />
		<button class="input__button {rightIcon ? 'true' : 'hide'}"
			><img src={rightIcon} alt="#" /></button
		>
	</div>
</main>

<style>
	.hide {
		display: none;
	}

	.input__enter {
		width: 100%;
		border: none;
		outline: none;
		background: #c9ebfc;
		height: 100%;
	}

	.input__wrap {
		display: flex;
		align-items: center;
		width: 424px;
		border: 1px solid #c9ebfc;
		border-radius: 6px;
		padding: 16px;
		background-color: #c9ebfc;
	}
</style>
