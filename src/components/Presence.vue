<template>
	<div>
		<table v-if="data" class="table table-dark">
			<thead>
				<tr>
					<td>#</td>
					<th scope="col">Lundi</th>
					<th scope="col">Mardi</th>
					<th scope="col">Mercredi</th>
					<th scope="col">Jeudi</th>
					<th scope="col">Vendredi</th>
					<th scope="col">Samedi</th>
					<th scope="col">Dimanche</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<th scope="row">Amita</th>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.lundi.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mardi.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mercredi.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.jeudi.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.vendredi.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.samedi.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.dimanche.amita">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
				</tr>
				<tr>
					<th>Lifer</th>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.lundi.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mardi.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mercredi.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.jeudi.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.vendredi.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.samedi.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.dimanche.lifer">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
				</tr>
				<tr>
					<th>Exil</th>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.lundi.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mardi.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mercredi.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.jeudi.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.vendredi.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.samedi.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.dimanche.exil">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
				</tr>
				<tr>
					<th>ZEQ</th>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.lundi.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mardi.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mercredi.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.jeudi.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.vendredi.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.samedi.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.dimanche.zeq">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
				</tr>
				<tr>
					<th>Zlak</th>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.lundi.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mardi.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.mercredi.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.jeudi.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.vendredi.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.samedi.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
					<td>
						<div class="pretty p-icon p-round p-pulse">
							<input type="checkbox" v-model="data.dimanche.zlak">
							<div class="state p-success">
								<i class="icon mdi mdi-check"></i>
								<label></label>
							</div>
						</div>
					</td>
				</tr>
			</tbody>
		</table>
		<button class="btn btn-secondary submit" @click="sendData">Envoyer</button>
		<div id="alert-area" class="alert-area"></div>
	</div>
</template>

<script>
    import $ from 'jquery';
    import firebase from 'firebase';
    import config from '../../config.json';

    export default {
        name: 'presence',
        data() {
            return {
                data: null,
                ref: null
            }
        },
        methods: {
            // The main class
            AlertBox(option) {
                this.show = (msg) => {
                    if (msg === ''  || typeof msg === 'undefined' || msg === null) {
                        throw '"msg parameter is empty"';
                    }
                    else {
                        const alertArea = document.querySelector('#alert-area');
                        const alertBox = document.createElement('DIV');
                        const alertContent = document.createElement('DIV');
                        const alertClose = document.createElement('A');
                        const alertClass = this;
                        alertContent.classList.add('alert-content');
                        alertContent.innerText = msg;
                        alertClose.classList.add('alert-close');
                        alertClose.setAttribute('href', '#');
                        alertBox.classList.add('alert-box');
                        alertBox.appendChild(alertContent);
                        if (!option.hideCloseButton || typeof option.hideCloseButton === 'undefined') {
                            alertBox.appendChild(alertClose);
                        }
                        alertArea.appendChild(alertBox);
                        alertClose.addEventListener('click', (event) => {
                            event.preventDefault();
                            alertClass.hide(alertBox);
                        });
                        if (!option.persistent) {
                            const alertTimeout = setTimeout(() => {
                                alertClass.hide(alertBox);
                                clearTimeout(alertTimeout);
                            }, option.closeTime);
                        }
                    }
                };

                this.hide = (alertBox) => {
                    alertBox.classList.add('hide');
                    const disperseTimeout = setTimeout(() => {
                        alertBox.parentNode.removeChild(alertBox);
                        clearTimeout(disperseTimeout);
                    }, 500);
                };
            },
            initializeState() {
                firebase.initializeApp(config);
                const database = firebase.database();
                this.ref = database.ref('presence');
                this.ref.on('value', (data) => {
                    this.data = data.val();
                });
            },
            sendData() {
                const alertbox = new this.AlertBox({
                    closeTime: 5000,
                    persistent: false,
                    hideCloseButton: false
                });
                this.ref.update(this.data).then(() => {
                    alertbox.show('It\'s done my friend');
                }).catch( (error) => {
                    alert(error);
                });
            }
        },
        mounted() {
            this.data = this.initializeState();

        }
    }
</script>

<style scoped>
	img {
		width: 100px;
		margin:10px;
	}
	table {
		width: 50%;
		margin: auto;
	}

	.submit {
		margin-top:20px;
	}

	/* ALERT RELATED CLASS (START) */

	.alert-area {
		max-height: 100%;
		position: fixed;
		bottom: 5px;
		left: 20px;
		right: 20px;
		color: #155724;
		background-color: #d4edda;
	}

	.alert-box {
		font-size: 16px;
		line-height: 1.3em;
		padding: 10px 15px;
		margin: 5px 10px;
		position: relative;
		border-radius: 5px;
		transition: opacity 0.5s ease-in;
	}

	.alert-content {
		color: white!important;
	}

	.alert-box.hide {
		opacity: 0;
	}

	.alert-close {
		background: transparent;
		width: 12px;
		height: 12px;
		position: absolute;
		top: 15px;
		right: 15px;
	}

	.alert-close:before,
	.alert-close:after {
		content: '';
		width: 15px;
		border-top: solid 2px white;
		position: absolute;
		top: 5px;
		right: -1px;
		display: block;
	}

	.alert-close:before {
		transform: rotate(45deg);
	}

	.alert-close:after {
		transform: rotate(135deg);
	}

	.alert-close:hover:before,
	.alert-close:hover:after {
		border-top: solid 2px #d8d8d8;
	}

	@media (max-width: 767px) and (min-width: 481px) {
		.alert-area {
			left: 100px;
			right: 100px;
		}
	}

	@media (min-width: 768px) {
		.alert-area {
			width: 350px;
			left: auto;
			right: 0;
		}
	}

	/* ALERT RELATED CLASS (END) */

	.alert-message-container {
		text-align: center;
		line-height: 2.5em;
		margin-top: 50px;
	}

	.alert-message-box {
		font-size: 20px;
		width: 300px;
		border: solid 1px #fff;
		padding: 10px 15px;
		outline: none;
		transition: box-shadow 0.1s;
	}

	.alert-message-box:focus {
		box-shadow: 0 0 15px 2px #888;
	}

</style>
