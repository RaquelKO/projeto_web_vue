<template>
  <v-app>
		
    <v-system-bar app >
			<v-row justify="center">
				<strong>v-system-bar</strong>
			</v-row>
    </v-system-bar>

		<v-navigation-drawer app >
			<v-col align="center">
				<strong>v-navigation-drawer</strong>
			</v-col>
		</v-navigation-drawer>

		<v-app-bar app>
				<v-row justify="center">
					<strong>v-app-bar</strong>
			</v-row>
		</v-app-bar>

		<v-container fill-height fluid>
			<v-content>
				<v-row align="center">
					<v-col class="text-center">
						<strong>v-content</strong>
					</v-col>
				</v-row>
			</v-content>
		</v-container>

		<v-footer height="30px" app>
			<v-row justify="center">
				<strong>v-footer</strong>
			</v-row>
		</v-footer>

		<v-bottom-navigation app>
			<v-row align="center" justify="center">
				<strong>v-bottom-navigation</strong>
			</v-row>
		</v-bottom-navigation>

  </v-app>
</template>

<script>
  export default {
    data: () => ({
      links: [],
    }),
  }
</script>
