<template>
	<main>
		<section class="section-people">
			<div class="container">
				<ul class="section-people-list">
					<li class="section-people-item">
						<img class="section-people-img" src="../img/Avatar.png" />
						<div class="section-people-item__box">
							<h3 class="section-people-title">Алексей Миногаров</h3>
							<span class="section-people-profession">mi</span>
							<p class="section-people-profession">Analyst</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Алиса Иванова</h3>
							<span>al</span>
							<p>Designer</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Андрей Иванов</h3>
							<span>iv</span>
							<p>Designer</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Анна Иванова</h3>
							<span>an</span>
							<p>Analyst Team Lead</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Анна Смирнова</h3>
							<span>sm</span>
							<p>Analyst</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Влада Вейн</h3>
							<p>Manager</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Дана Хаматова</h3>
							<p>Manager</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Иван Андреенко</h3>
							<span>va</span>
							<p>Analyst</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Инга Антонова</h3>
							<span>ai</span>
							<p>Designer</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Ирен Адлер</h3>
							<p>Manager</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Ольга Петрова</h3>
							<span>po</span>
							<p>Analyst</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Ольга Сергеевна</h3>
							<span>so</span>
							<p>Designer</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Павел Волков</h3>
							<span>vp</span>
							<p>Art-Director</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Петр Сиша</h3>
							<span>pe</span>
							<p>Analyst</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Саймон Кит</h3>
							<p>Team Lead</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Светлана Осипова</h3>
							<span>os</span>
							<p>Analyst</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Стас Петрич</h3>
							<span>ps</span>
							<p>Designer</p>
						</div>
					</li>
					<li>
						<img />
						<div>
							<h3>Улан Капелов</h3>
							<span>mi</span>
							<p>Analyst</p>
						</div>
					</li>
				</ul>
			</div>
		</section>
	</main>
</template>

<script>
export default {
	name: "List"
}
</script>

<style lang="scss" scoped>
// .section-people-img {
// 	width: 10%;
// 	height: auto;
// }

.section-people-item {
	display: flex;
	flex-direction: row;
	margin: 22px auto 12px 16px;

	&__box {
		margin: 38px auto 30px 16px;
	}
}
</style>