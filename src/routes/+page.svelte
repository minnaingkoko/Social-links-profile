<script>
	import img from '$lib/images/avatar-jessica.jpeg';
</script>

<div class="container">
	<img class="profile" src={img} alt="" />
	<div class="name">Jessica Randall</div>
	<div class="address">London, United Kingdom</div>
	<div class="job">"Front-end developer and avid reader."</div>
	<div class="links">
		<div class="link">Github</div>
		<div class="link">Frontend Mentor</div>
		<div class="link">LinkedIn</div>
		<div class="link">Twitter</div>
		<div class="link">Instagram</div>
	</div>
</div>

<style>
	.container {
		width: 384px;
		height: 611px;
		border-radius: 12px;
		background-color: #1f1f1f;
		display: flex;
		flex-direction: column;
		align-items: center;
		padding: 40px;
	}
	.profile {
		width: 88px;
		height: 88px;
		object-fit: cover;
		border-radius: 100%;
	}
	.name {
		margin-top: 24px;
		font-family: 'Inter-Bold', sans-serif;
		font-size: 24px;
	}
	.address {
		margin-top: 4px;
		font-family: 'Inter-Bold', sans-serif;
		font-size: 14px;
		color: #c4f82a;
	}
	.job {
		margin-top: 24px;
		font-size: 14px;
	}
	.links {
		margin-top: 24px;
		display: flex;
		flex-direction: column;
		gap: 16px;
	}
	.link {
		width: 304px;
		height: 45px;
		display: flex;
		justify-content: center;
		align-items: center;
		font-family: 'Inter-Bold', sans-serif;
		font-size: 14px;
		background-color: #333333;
		border-radius: 8px;
		cursor: pointer;
		transition: 0.3s ease-out;
	}
	.link:hover {
		background-color: #c4f82a;
		color: #333333;
	}

	@media only screen and (max-width: 920px) {
		.container {
			width: 456px;
		}
		.link {
			width: 376px;
		}
	}
    @media only screen and (max-width: 375px) {
        .container {
			width: 327px;
            height: 579px;
            padding: 24px;
		}
        .link {
			width: 279px;
		}
    }
</style>
