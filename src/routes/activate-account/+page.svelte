<script lang="ts">
    /*
    import { onMount } from 'svelte';
    import { goto } from "$app/navigation";
    import { get } from 'svelte/store';
    import { verifyEmail, verifyEmailResponse } from "$lib/stores/sessions/initiation";  
    import { makeRandomId } from '$lib/makeRandomId';
    import { showLoading } from '$lib/stores/showLoading';
    showLoading.set('visible');

    let loading = "visible";
    let errorAlert = "invisible";
    let successVerifyAlert = false;
    let wrongLinkVerify = false;
    let WrongEmailCode = false;

    onMount(() => {
        const urlParams = new URLSearchParams(window.location.search);
        const email = urlParams.get('email');
        const type = urlParams.get('type');
        const emailcode = urlParams.get('emailcode'); 

        if ((email)&&(type)&&(emailcode)&&(emailcode.length === 6)&&(type === "activate")) {  

            verifyEmail.set(JSON.stringify({ 
                "messageType":"verifyEmail", 
                "verifyType":type, 
                "email":email, 
                "random": makeRandomId(6),
                "code":emailcode 
            }));
   
        }else{
            loading = "invisible";
            wrongLinkVerify = true;
            errorAlert = "visible";
        }
        showLoading.set('invisible');
    })

    $:if($verifyEmailResponse){
        loading = "invisible";
        // @ts-ignore
        let JsonResponse = JSON.parse(get(verifyEmailResponse));
        if(JsonResponse.message === 'OK'){                    
            successVerifyAlert = true;
        }else if(JsonResponse.message === 'WrongEmailCode'){   
            errorAlert = "visible";                 
            WrongEmailCode = true;
        }else{                     
            errorAlert = "visible";
        }
    }
    */
</script>
<!--
<div class="container min-h-screen px-12">    
    <span class="loading loading-spinner loading-lg fixed top-1/3 left-1/2 -translate-y-1/3 -translate-x-1/2 z-10 {loading}"></span>    
    <div class="fixed top-1/3 left-1/2 -translate-y-1/3 -translate-x-1/2 z-10 {errorAlert}">
        <div class="modal-box">
            <h3 class="font-bold text-2xl py-4 text-red-500">Verify email error!</h3>    
            {#if successVerifyAlert}       
                <div class="py-1">Verify email link is not correct. Check your email, link and try again later.</div>
            {/if}
            {#if WrongEmailCode}       
                <div class="py-1">Wrong verify code in verify link. Request verify email again and check your email.</div>
            {/if}
            <div class="py-1">Unknow network error occur. Email can not verify at the moment. Please try again later.</div>
            <div class="modal-action">
                <form method="dialog">
                    <button class="btn" on:click = {() => errorAlert = "invisible"}>Close</button>
                </form>
            </div>
        </div>
    </div>
</div>

{#if successVerifyAlert}
<div class="fixed top-1/3 left-1/2 -translate-y-1/3 -translate-x-1/2 z-10">
    <div class="modal-box">
      <h3 class="font-bold text-2xl py-4 text-blue-600">Email has been verified</h3>
      <p>Your registration email at kibibase.com has been verified successful.</p>
      <div class="modal-action">
        <form method="dialog">
          <button class="btn" on:click = {() => goto("/pages/dashboard") }>Close</button>
        </form>
      </div>
    </div>
</div>
{/if}
-->