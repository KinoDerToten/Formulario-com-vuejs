<template>
    <main>
        <div class="container">
            <div class="row h-100">
                <div class="col-12 col-lg-6">
                    <div class="row h-100">
                        <div class="col-12">
                            <h1 class="text-white">Learn to code by watching others</h1>
                            <p class="text-white">
                                See how experienced developers solve problems in real-time. Watching scripted tutorials is great,
                                but understanding how developers think is invaluable.
                            </p>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-6 mt-5 mt-lg-0">
                    <div class="row">
                        <div class="col-11 m-auto oferta">
                            <a href="" class="m-auto w-50"><strong>Try it free 7 days</strong> then $20/mo. thereafter</a>
                        </div>
                        <div class="col-11 m-auto p-0 mt-5 mb-5">
                            <form action="" class="bg-white p-3 p-lg-5">
                                <input type="text" class="form-control p-3 p-lg-4 mb-4" id="FirstName" placeholder="First Name">
                                <input type="text" class="form-control p-3 p-lg-4 mb-4" id="LastName" placeholder="Last Name">
                                <input type="email" class="form-control p-3 p-lg-4 mb-4" id="email" placeholder="Email Address">
                                <input type="password" class="form-control p-3 p-lg-4 mb-4" placeholder="Password">
                                <a href="" class="button-submit"><strong>CLAIM YOUR FREE TRIAL</strong></a>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>

</script>

<style scoped>

    .container{
        height: 650px;
        margin-top: 100px;
    }

    .container h1{
        font-size: 70px;
    }

    .container p{
        font-size: 21px;
    }

    form{
        border-radius: 5px;
        height: 535px;
        box-shadow: 0 10px #db686b;
    }

    .oferta{
        padding: 20px 0;
        background: #5d54a3;
        border: 1px solid #6a5195;
        text-align: center;
        border-radius: 5px;
        box-shadow: 0 10px #db686b;
    }

    a{
        display: block;
        text-decoration: none;
        color: #FFF;
    }

    .button-submit{
        padding: 20px 0;
        background: #77e2b4;
        border: 1px solid #93d3b9;
        border-radius: 5px;
        box-shadow: inset 0px -5px #76c8a4;
        text-align: center;
    }

    @media (max-width: 991px){
        .container h1{
            font-size: 40px;
            text-align: center;
        }

        .container p{
            font-size: 19px;
            text-align: center;
            margin-top: 25px;
        }

        form{
            height: 420px;
        }
    }
    
</style>