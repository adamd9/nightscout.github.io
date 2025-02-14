# Heroku Basic plan upgrade

<span style="font-size:smaller;">**APPLIES TO:**</span>	<img src="../../img/Heroku.png" style="zoom:80%;" />

</br>

## [End of Free plan](https://blog.heroku.com/next-chapter)

Starting October 26, 2022, Heroku began deleting accounts that have been inactive for over a year.

Starting November 28, 2022, Heroku stopped offering free product plans and start shutting down free dynos and data services. Free accounts are converted to Eco plan with dynos sized zero (i.e. stopped without billing).

This means that if you wish to continue using Heroku you need to upgrade your plan.

</br>

!!!info "Too complicated? Not what you're looking for? Consider a hosted Nightscout service! Check for easier solutions [here](../../../#nightscout-as-a-service)."  
<span style="font-size:larger;">Interested in building a Nightscout DIY site?  Make sure you **read and understand [this](/#how-much-does-it-cost)** before starting.</span>

</br>

**Pros**:  

> Heroku is a reliable platform well known by the community  
> The Basic plan is designed for production, the app never sleeps  
> Heroku has been hosting Nightscout users for years in the free tier  

**Cons**:  

>Using the M0 [MongoDB Atlas](../../mongodb/atlas/) database  
>The [Eco plan](../ecoplan) is more economical  
>Paying for a Basic plan doesn't remove DIY maintenance tasks like stack upgrade  

</br>

## Upgrade to 7$/month Basic Plan

!!!note "5$/month Eco Plan"  
    You can also select an [eco plan upgrade](../ecoplan). You can easily change plan.

</br>

- Log in Heroku [https://id.heroku.com/login](https://id.heroku.com/login)

<img src="../../../update/img/UpdateNS15.png" style="zoom:80%;" >

</br>

- Select your app (hidden in yellow)

<img src="../../../update/img/UpdateNS16.png" style="zoom:80%;" >

</br>

- Click `Resources` then select `Change Dyno Type`

<img src="../../heroku/img/HerokuH01.png" style="zoom:90%;" >

</br>

- Select `Basic ($7/dyno/month)` then click `Save`

<img src="../../heroku/img/HerokuH02.png" style="zoom:80%;" >

</br>

- Your Nightscout Heroku app is now using a `Basic` plan.  
  *Note: if you were doing a test you still can return to an `Eco` dyno plan for now.*

<img src="../../heroku/img/HerokuH03.png" style="zoom:80%;" >

- **Make sure your credit card information is up to date!**  
  Go to your `Account settings`.

<img src="../../../nightscout/img/NewNS13.png" style="zoom:80%;" >

- `Billing`

<img src="../../../nightscout/img/NewNS14.png" style="zoom:80%;" >

- Verify the credit card you used is still valid, in case of doubt `Change credit card` and enter a valid credit card.

<img src="../../heroku/img/HerokuH04.png" style="zoom:80%;" >

</br>

