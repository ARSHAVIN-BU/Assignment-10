<template>
    <div>
        <Navbar />
        <section class="contact">

            <h1 class="heading"> contact <span>me</span> </h1>

            <div class="row">

                <div class="info-container">

                    <h1>get in touch</h1>

                    <p> สนใจหาคนคุย Inbox ได้เลยครับ 5555 </p>

        <div class="box-container">

            <div class="box">
                <i class="fas fa-map"></i>
                <div class="info">
                    <h3>address :</h3>
                    <p>{{address}}</p>
                </div>
            </div>

            <div class="box">
                <i class="fas fa-envelope"></i>
                <div class="info">
                    <h3>email :</h3>
                    <p>{{email}}</p>
                </div>
            </div>

            <div class="box">
                <i class="fas fa-phone"></i>
                <div class="info">
                    <h3>number :</h3>
                    <p>{{number}}</p>
                </div>
            </div>

        </div>

        <div class="share">
            <a href="#" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-twitter"></a>
            <a href="#" class="fab fa-instagram"></a>
            <a href="#" class="fab fa-linkedin"></a>
        </div>

    </div>

                <form action="">

                    <div class="inputBox">
                        <input type="text" placeholder="your name">
                        <input type="number" placeholder="your number">
                    </div>

                    <div class="inputBox">
                        <input type="email" placeholder="your email">
                        <input type="text" placeholder="your subject">
                    </div>

                    <textarea name="" placeholder="your message" id="" cols="30" rows="10"></textarea>

                    <input type="submit" value="send message" class="btn">

                </form>

            </div>

        </section>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: { Navbar },
    data() {
        return {
            address: 'Phathumtani, Thailand 12120'
              email: 'arshavin.jaru@bumail.net'
             number: '+6649746466'  
        }
    }
}
</script>

<style>

</style>