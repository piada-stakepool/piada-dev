
<script>
    import perfData from '$lib/data/poolData.json';
    
    /*
	let getPoolUptime = (async () => {
		const res = await fetch(
			'https://api.uptimerobot.com/v2/getMonitors?format=json&api_key=ur1967275-b3b281dc8596ed10791ab890', { method: 'POST' }
		);
		return await res.json();
	})();
    */

    let teddy = "https://fiso.teddyswap.org/teddy-logo.svg";
    let tosi = "https://app.tosidrop.io/static/media/tosidrop-dark.a0c16f6bb65f98d229a5.png";
    let aaShip = "/aa-ship.gif";
</script>

<div class="w3-container" id="performance" style="background-color:#4285af;">
    <div class="w3-row w3-center w3-text-white" style="padding:84px 0px">
        <div class="w3-col l2 m12 s12 w3-padding-32 w3-large">
            <span class="w3-xxlarge">{perfData.total_delegated}+</span>&#8371;<br>
            Pool Delegation
        </div>
        <div class="w3-col l2 m12 w3-mobile w3-padding-32 w3-large">
            <span class="w3-xxlarge">{perfData.pledge}</span>&#8371;<br>
            Pool Pledge
        </div>
        <div class="w3-col l2 m12 w3-mobile w3-padding-32 w3-large">
            <span class="w3-xxlarge">{perfData.block_count}</span><br>
            Lifetime Pool Blocks
        </div>
        <div class="w3-col l2 m12 w3-mobile w3-padding-32 w3-large">
            <span class="w3-xxlarge">{perfData.life_time_ros}%</span><br>
            Lifetime Return on Stake
        </div>
        <div class="w3-col l2 m12 w3-mobile w3-padding-32 w3-large">
            <span class="w3-xxlarge">{perfData.pool_fee}%</span><br>
            Low Variable Pool Fee
        </div>
        <div class="w3-col l2 m12 w3-mobile w3-padding-32 w3-large">
            <span class="w3-xxlarge">{perfData.delegate_rewards}</span>&#8371;<br>
            Lifetime Rewards to Delegates
        </div>
    </div>

    <div class="w3-row w3-center w3-black w3-round-xlarge" style="padding:84px 0px;margin-bottom:16px;">
        <div class="w3-col w3-mobile">
            <a href="https://armada-alliance.com/docs" rel="noreferrer" target="_blank"><img src="{aaShip}" class="w3-image aa-logo" alt="Armada Alliance" width="300"></a>
            <p class="armada w3-xlarge w3-text-white">Learn about Cardano stakepool operations and development using a Raspberry Pi in the <a href="https://armada-alliance.com/docs" rel="noreferrer" target="_blank">Armada Alliance</a></p>
        </div>
    </div>
    <div class="w3-row w3-center w3-black w3-round-xlarge" style="padding:84px 0px;margin-bottom:16px;">
        <div class="w3-col w3-mobile">
            <a href="https://adastry.io" rel="noreferrer" target="_blank"><svg xmlns="http://www.w3.org/2000/svg" height="140px" viewBox="0 0 178 210"><title>Adastry.io</title><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g transform="translate(0.619006, 0.337855)" fill-rule="nonzero"><g transform="translate(0.000000, -0.000000)"><path style="fill: #fff" d="M82.5107909,3.36958152 L82.5107909,3.36958152 C114.488078,3.36958152 140.410791,29.2922945 140.410791,61.2695815 L140.410791,205.369582 L140.410791,205.369582 C108.433504,205.369582 82.5107909,179.446869 82.5107909,147.469582 L82.5107909,3.36958152 Z" id="Layer_1-2" fill="#FFFFFF" transform="translate(111.460791, 104.369582) rotate(157.400000) translate(-111.460791, -104.369582) "></path><path class="permanent" d="M65.6910018,161.722152 C62.6210018,154.352152 60.1110018,146.782152 57.6910018,139.192152 C54.4496604,128.678177 45.6267222,120.841653 34.803709,118.863684 C23.9806958,116.885716 12.9563115,121.095026 6.20571745,129.782917 C-0.544876558,138.470809 -1.89978205,150.193418 2.69100184,160.192152 C3.81930296,162.746333 5.30040797,165.129566 7.09100184,167.272152 C22.8933598,188.843402 51.4122215,196.787351 76.0910018,186.492152 L65.6910018,161.722152 Z" id="Layer_1-2" fill="#7cb342"></path></g></g></g></svg></a>
            <p class="adastry w3-xlarge">Delegates to PIADA qualify for free <a href="https://adastry.io" rel="noreferrer" target="_blank">Adastry.io</a> wallet services after 4 epochs</p>
        </div>
    </div>
    <div class="w3-row w3-center w3-black w3-round-xlarge" style="padding:84px 0px;margin-bottom:16px;">
        <div class="w3-col w3-mobile">
            <a href="https://teddyswap.org" rel="noreferrer" target="_blank"><img src="{teddy}" class="w3-image teddy-logo" alt="" width="600"></a>
            <p class="teddy w3-xlarge">Earn $TEDY tokens by delegating to PIADA during the <a href="https://teddyswap.org" rel="noreferrer" target="_blank">TeddySwap FISO</a> starting at epoch 392</p>
        </div>
    </div>
    <div class="w3-row w3-center w3-black w3-round-xlarge" style="padding:84px 0px;margin-bottom:16px;">
        <div class="w3-col w3-mobile">
            <a href="https://app.tosidrop.io/cardano/claim" rel="noreferrer" target="_blank"><img src="{tosi}" class="w3-image teddy-logo" alt="" width="600"></a>
            <p class="teddy w3-xlarge"><a href="https://app.tosidrop.io/cardano/claim" rel="noreferrer" target="_blank">TosiDrop</a> tokens coming soon!</p>
        </div>
    </div>
    

    <!--
    <div class="w3-row w3-center w3-black w3-round-xlarge" style="padding:84px 0px;margin-bottom:16px;">
        <div class="w3-row-padding w3-center" style="margin-top:84px!important">
            {#await getPoolUptime}
            <div class="w3-center w3-padding-32">
                <p class="w3-large">Loading Relay Statuses</p>
            </div>
            {:then data}
                {#if data.stat === "ok"}
                    {#if data.monitors[0].status === 2}
                    <div class="w3-third">
                        <i class="fa-solid fa-heart-circle-check fa-beat-fade w3-margin-bottom w3-jumbo w3-text-green" style="--fa-animation-duration: 2s; --fa-beat-fade-opacity: 0.67; --fa-beat-fade-scale: 1.055;"></i>
                        <p class="w3-large">Relay 1 is doing just fine</p>
                    </div>
                    {:else}
                    <div class="w3-third">
                        <i class="fa-solid fa-heart-crack w3-margin-bottom w3-jumbo w3-text-red"></i>
                        <p class="w3-large">Relay 1 is undergoing maintenance</p>
                    </div>
                    {/if}
                    <div class="w3-third w3-padding-32">
                        <i class="fa-solid fa-circle w3-margin-bottom w3-tiny w3-text-green"></i><span class="w3-xlarge" style="padding-left:5px;"><a href="https://stats.uptimerobot.com/lgx2rF184V" rel="no-referrer" target="_blank">UptimeRobot</a></span>
                    </div>
                    {#if data.monitors[1].status === 2}
                    <div class="w3-third">
                        <i class="fa-solid fa-heart-circle-check fa-beat-fade w3-margin-bottom w3-jumbo w3-text-green"></i>
                        <p class="w3-large">Relay 2 is doing just fine</p>
                    </div>
                    {:else}
                    <div class="w3-third">
                        <i class="fa-solid fa-heart-crack w3-margin-bottom w3-jumbo w3-text-red"></i>
                        <p class="w3-large">Relay 2 is undergoing maintenance</p>
                    </div>
                    {/if}
                {:else}
                <div class="w3-center w3-padding-32">
                    <p class="w3-large">No UptimeRobot API Available</p>
                </div>
                {/if}
            {:catch error}
            <div class="w3-center w3-padding-32">
                <p class="w3-large">No UptimeRobot API Available</p>
            </div>
            {/await}
        </div>
    </div>
    -->
</div>

<style>
.w3-col {text-shadow:1px 1px 4px #000;}
.w3-col .adastry,.w3-col .teddy,.w3-col .armada {text-shadow:1px 1px 0 #131522;}
.teddy-logo {
    /*max-height: 600px;
    max-width: 600px;*/
    margin-bottom: 13px;
    padding:10px;
}
.aa-logo {
    /*max-height: 600px;
    max-width: 600px;*/
    margin-bottom: 13px;
    padding:10px;
}
</style>
