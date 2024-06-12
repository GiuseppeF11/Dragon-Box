<script>
import AppHeader from '../components/AppHeader.vue';
import AppFooter from '../components/AppFooter.vue';

export default {
    data(){
        return{
            slideUno:[
                {
                    image: 'https://i.ebayimg.com/images/g/mGMAAOSwdUdjM4BG/s-l1200.webp',
                    desc: 'Goku in action',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://i.pinimg.com/736x/72/9e/e3/729ee3b542324b9e1b1b4d88180b0b49.jpg',
                    desc: 'Vegeta the Prince of Saiyans',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://i.pinimg.com/736x/f4/b0/72/f4b0724b1cd4e6bce148f7957a795d42.jpg',
                    desc: 'Gohan Beast',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://images.everyeye.it/img-notizie/dragon-ball-super-livello-potenza-esatto-ammonta-orange-piccolo-v3-662080-1200x1200.webp',
                    desc: 'Piccolo the wise warrior',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://i.ebayimg.com/images/g/9iYAAOSwp~tixozW/s-l1600.jpg',
                    desc: 'Future Trunks with his sword',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://images.everyeye.it/img-notizie/dragon-ball-cosplay-bulma-adulta-abito-rosso-pam-v3-639959-1200x1200.webp',
                    desc: 'Bulma the brilliant scientist',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://images.fineartamerica.com/images/artworkimages/mediumlarge/3/golden-freezer-artwork-big-mart.jpg',
                    desc: 'Frieza the galactic tyrant',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/c741ffe5-60c6-480c-ac38-86c623a52889/dfz99nw-c71a5938-4d50-4d87-920c-003654cfce27.png/v1/fill/w_1024,h_1536,q_80,strp/perfect_cell___dragon_ball_z_by_yomogun_dfz99nw-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2M3NDFmZmU1LTYwYzYtNDgwYy1hYzM4LTg2YzYyM2E1Mjg4OVwvZGZ6OTludy1jNzFhNTkzOC00ZDUwLTRkODctOTIwYy0wMDM2NTRjZmNlMjcucG5nIiwiaGVpZ2h0IjoiPD0xNTM2Iiwid2lkdGgiOiI8PTEwMjQifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uud2F0ZXJtYXJrIl0sIndtayI6eyJwYXRoIjoiXC93bVwvYzc0MWZmZTUtNjBjNi00ODBjLWFjMzgtODZjNjIzYTUyODg5XC95b21vZ3VuLTQucG5nIiwib3BhY2l0eSI6OTUsInByb3BvcnRpb25zIjowLjQ1LCJncmF2aXR5IjoiY2VudGVyIn19.s-sq2ahHijCPliYieZbO7vT45RLq27OeHdPjFGE8Qxo',
                    desc: 'Cell the bio-engineered android',
                    date: 'December 25, 2022',
                },
                {
                    image: 'https://s1.zerochan.net/Majin.Buu.600.3602407.jpg',
                    desc: 'Majin Buu the unpredictable',
                    date: 'December 25, 2022',
                },
            ],
            videos: [
                {
                    thumb:'https://cloudfront-eu-central-1.images.arcpublishing.com/diarioas/QCSKO3BSYVAB5CD5CUV3KLJKRQ.jpg',
                    num: 1,
                    title: 'Goku vs Vegeta: Epic Battle'
                },
                {
                    thumb:'https://static1.thegamerimages.com/wordpress/wp-content/uploads/2018/12/Dragon-Ball-Resurrection-F-Master-Roshi-e1545397478625.jpg',
                    num: 2,
                    title: 'Training with Master Roshi' 
                },
                {
                    thumb:'https://www.mundodeportivo.com/alfabeta/hero/2022/11/Goku-ultra-instinto-no-es-una-transformacion.png?width=768&aspect_ratio=16:9&format=nowebp',
                    num: 3,
                    title: 'Top 10 Legendary Goku Moments' 
                },
                {
                    thumb:'https://i0.wp.com/www.badtaste.it/fumetti/wp-content/uploads/sites/3/frieza-2015.jpg?fit=600%2C300&quality=85&strip=all&ssl=1',
                    num: 4,
                    title: 'Everytime Frieza Makes an Entrance' 
                },
                {
                    thumb:'https://i.ytimg.com/vi/qBA9o7qEhCQ/maxresdefault.jpg',
                    num: 5,
                    title: 'Goku vs Vegeta: Final Showdown'
                },
                {
                    thumb:'https://i.pinimg.com/originals/14/83/55/14835580b9fd40fb3f8c921f7c1d8c6a.jpg',
                    num: 6,
                    title: "Goku's Training Journey"
                },
                {
                    thumb:'https://static1.cbrimages.com/wordpress/wp-content/uploads/2021/07/dragon-ball-super-piccolo-smiles-header.jpg',
                    num: 7,
                    title: "Piccolo's Strategy"
                }
            ],

            slideDue:[
            {
                    image: 'https://images.stockx.com/images/Funko-Pop-Animation-Dragon-Ball-Super-SSG-Goku-Summer-Convention-Exclusive-Figure-826.jpg?fit=fill&bg=FFFFFF&w=1200&h=857&fm=webp&auto=compress&dpr=2&trim=color&updated_at=1607122933&q=60',
                    desc: 'Goku SSG',
                    price: '30,00€'
                },
                {
                    image: 'https://nuovo.uomodeifumetti.it/wp-content/uploads/2023/07/889698658935.webp',
                    desc: 'Goku Ultra Instinct',
                    price: '50,00€'
                },
                {
                    image: 'https://m.media-amazon.com/images/I/818U+PYaavL._UF1000,1000_QL80_.jpg',
                    desc: 'Shenron Dragon',
                    price: '20,00€'
                },
                {
                    image: 'https://www.thegamebusters.it/22841-large_default/funko-pop-kami-952-dragon-ball.jpg',
                    desc: 'Supremo',
                    price: '15,00€'
                },
                {
                    image: 'https://www.ibs.it/images/0849803039912_1_536_0_75.jpg',
                    desc: 'Vegeta DBZ',
                    price: '30,00€'
                },
                {
                    image: 'https://images.stockx.com/images/funko-pop-animation-dragonball-z-beerus-flocked-funimation-exclusive-figure-514-Updated.jpg?fit=fill&bg=FFFFFF&w=700&h=500&fm=webp&auto=compress&q=90&dpr=2&trim=color&updated_at=1626289848',
                    desc: 'Beerus',
                    price: '30,00€'
                },
                {
                    image: 'https://i0.wp.com/mitico.biz/wp-content/uploads/2023/05/Funko-Pop-Dragonball-Super-Shin-1283.jpg?fit=650%2C650&ssl=1',
                    desc: 'Super Shin',
                    price: '29,99€'
                },
                {
                    image: 'https://m.media-amazon.com/images/I/81FQ0u8MTqL._AC_UF1000,1000_QL80_.jpg',
                    desc: 'Goku Black Rosè',
                    price: '39,99€'
                },
                {
                    image: 'https://www.stickerpoint.it/images/funko-pop-animation-1280-dragonball-super-jiren.jpg',
                    desc: 'Jiren',
                    price: '50,00€'
                },
                    
                ],
            carouselFoot:[
                    {
                        image: '/public/anime-fashion.webp',
                        title:'FASHION',
                        desc:'3 POSTS'
                    },
                    {
                        image: '/public/success-story.webp',
                        title:'CULTURE',
                        desc:'3 POSTS'
                    },
                    {
                        image: '/public/healthy-foods.webp',
                        title:'FOOD',
                        desc:'3 POSTS'
                    },
                    {
                        image: '/public/visit-france.webp',
                        title:'LIFESTYLE',
                        desc:'3 POSTS'
                    },
                    {
                        image: '/public/travel-alone.webp',
                        title:'STORIES',
                        desc:'3 POSTS'
                    },
                    {
                        image: '/public/best-places.webp',
                        title:'TRAVEL',
                        desc:'3 POSTS'
                    }
                ],
        }
    },
    components: {
            AppHeader,
            AppFooter
        },
    mounted() {
        $('.slider').slick({
        slidesToShow: 4,
        slidesToScroll: 1,
        autoplay: true,
        infinite: true,
        autoplaySpeed:2000,
        draggable:true,
        swipeToSlide: true,
        pauseOnHover: false,
        prevArrow:'',
        nextArrow:''
        });
        
        $('.slider2').slick({
            slidesToShow: 3,
            slidesToScroll: 1,
            autoplay: true,
            infinite: true,
            autoplaySpeed:2000,
            draggable:true,
            swipeToSlide: true,
            pauseOnHover: false,
            prevArrow:'',
            nextArrow:''
            });
    },
    methods: {
        next() {
        $('.slider').slick('slickNext');
        },

        next2(){
            $('.slider2').slick('slickNext');
            },

        prev() {
        $('.slider').slick('slickPrev');
        },

        prev2(){
            $('.slider2').slick('slickPrev');
            },

        handleMouseOver() {
        $('.slider').slick('slickPause');
        },

        handleMouseLeave() {
        $('.slider').slick('slickPlay');
        }
    },
};

</script>

<template>

    <AppHeader />

    <main>
        <section class="bg-section mb-4">
            <div class="slider" @mouseover="handleMouseOver" @mouseleave="handleMouseLeave">
                <div class="card" style="width: 18rem;" v-for="(slide,i) in slideUno">
                    <div class="card-img-box position-relative">
                        <img :src="slide.image" class="card-img-top" alt="...">
                    </div>
                    <div class="card-body text-center position-absolute bottom-0 start-50 translate-middle-x">
                        <p class="fw-bold text-light badge bg-dark fs-6">{{ slide.desc }}</p>
                        <!-- <p class="fw-semibold">{{ slide.date }}</p> -->
                    </div>
                </div>
            </div>

            <button class="my-button next" @click="prev"><i class="fa-solid fa-angle-left"></i></button>
            <button class="my-button prev" @click="next"><i class="fa-solid fa-angle-right"></i></button>
        </section>

        <div class="container">
            <section class="mb-5">      <!-- SEZIONE 2 COMPLETA -->
                <div class="row">
                    <div class="col-3 ">
                        <div class="card-section1">
                            <div class="card-section-main text-bg-dark border-0">
                                <img src="../../public/anime-fashion.webp" class="card-img" alt="...">
                                <div class="card-img-overlay card-poster">
                                    <div class="text-center ">
                                        <span class="badge  text-bg-light -3 mx-2 py-2 fw-semibold">Fashion</span>
                                        <span class="badge  text-bg-light -3 py-2 fw-semibold ">Lifestyle</span>
                                    </div>
                                    
                                    <div class="text-overlay text-center">
                                        <span><i class="fa-solid fa-user"></i></span>
                                        <span class="mx-2 fw-bold">demo</span>

                                        <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                        <span>December 25, 2022</span>
                                        <p class="card-text fw-bold">Fashion Trend Now a Days</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div>  
                            <div class="card-section-main text-bg-dark mt-3 border-0">
                                <img src="../../public/travel-alone-300x200.webp" class="card-img" alt="...">
                                <div class="card-img-overlay">
                                    <div class="text-center ">
                                        <span class="badge  text-bg-light -3 mx-2 py-2 fw-semibold">Stories</span>
                                        <span class="badge  text-bg-light -3 py-2 fw-semibold ">Travel</span>
                                    </div>
                                    <div class="text-overlay text-center">
                                        <span><i class="fa-solid fa-user"></i></span>
                                        <span class="mx-2 fw-bold">demo</span>

                                        <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                        <span>December 25, 2022</span>
                                        <p class="card-text fw-bold">Fashion Trend Now a Days</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col-6 ">
                        <div class="card-section-main text-bg-dark border-0">
                            <img src="../../public/best-places.webp" class="card-img" alt="...">
                            <div class="card-img-overlay">
                                <div class="text-center ">
                                        <span class="badge  text-bg-light -3 mx-2 py-2 fw-semibold">Lifestyle</span>
                                        <span class="badge  text-bg-light -3 py-2 fw-semibold ">Stories</span>
                                        <span class="badge  text-bg-light -3 py-2 mx-2 fw-semibold ">Travel</span>
                                </div>
                                <div class="text-overlay-center text-center">
                                    <span><i class="fa-solid fa-user"></i></span>
                                    <span class="mx-2 fw-bold">demo</span>

                                    <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                    <span>December 25, 2022</span>
                                    <p class="card-text fw-bold">Fashion Trend Now a Days</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col-3">
                        <div>
                            <div class="card-section-main text-bg-dark border-0">
                                <img src="../../public/music-love.webp" class="card-img" alt="...">
                                <div class="card-img-overlay">
                                    <div class="text-center ">
                                        <span class="badge  text-bg-light -3 mx-2 py-2 fw-semibold">Culture</span>
                                        <span class="badge  text-bg-light -3 py-2 fw-semibold ">Lifestyle</span>
                                    </div>
                                    <div class="text-overlay text-center">
                                        <span><i class="fa-solid fa-user"></i></span>
                                        <span class="mx-2 fw-bold">demo</span>

                                        <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                        <span>December 25, 2022</span>
                                        <p class="card-text fw-bold">Fashion Trend Now a Days</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div>
                            <div class="card-section-main text-bg-dark mt-3 border-0">
                                <img src="../../public/visit-france.webp" class="card-img" alt="...">
                                <div class="card-img-overlay">
                                    <div class="text-center ">
                                        <span class="badge  text-bg-light -3 py-2 fw-semibold ">Lifestyle</span>
                                        <span class="badge  text-bg-light -3 mx-2 py-2 fw-semibold">Travel</span>
                                    </div>
                                    <div class="text-overlay text-center">
                                        <span><i class="fa-solid fa-user"></i></span>
                                        <span class="mx-2 fw-bold">demo</span>

                                        <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                        <span>December 25, 2022</span>
                                        <p class="card-text fw-bold">Fashion Trend Now a Days</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
                


            </section>                  <!-- FINE SEZIONE 2 COMPLETA -->
        
            <section>                   <!-- SEZIONE 3 COMPLETA -->
                <div class="flex-section mb-2">
                    <div>
                        <h4>
                            LIFESTYLE & STORIES
                        </h4>
                    </div>

                    <div>
                        <span class="badge badge-pers">ALL</span>
                        <span class="badge badge-pers">LIFESTYLE</span>
                        <span class="badge badge-pers">STORIES</span>
                    </div>
                </div>

                <div class="row">
                    <div class="col-7">
                        <div class="card-section-main text-bg-dark mt-3 border-0">
                            <img src="../../public/music-love.webp" class="card-img" alt="...">
                            <div class="card-img-overlay padding-badge-pers">
                                <div class="">
                                    <span class="badge  text-bg-light -3 mx-2 py-2 fw-semibold">Culture</span>
                                </div>
                                <div class="text-overlay card-lifestyle-text">
                                    <span><i class="fa-solid fa-user"></i></span>
                                    <span class="mx-2 fw-bold">demo</span>

                                    <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                    <span>December 25, 2022</span>
                                    <p class="card-text fw-bold">Music The Love Of My life</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col-5">
                        <div class="flex-lifestyle">
                            <div class="card-section-main mt-3 border-0 card-lifestyle">
                                <img src="../../public/visit-france.webp" alt="" class="card-img">
                                <div class="card-img-overlay">
                                    
                                    <span class="badge text-bg-light -3 py-1 fw-semibold">Lifestyle</span>
                                    
                                </div>
                            </div>

                            <div class="mx-2">
                                <span><i class="fa-solid fa-user"></i></span>
                                <span class="mx-2 fw-bold">demo</span>

                                <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                <span>December 26, 2022</span>
                                <p class="card-text fw-bold">Music The Love Of My life</p>
                            </div>
                        </div>
                        <hr>

                        <div class="flex-lifestyle">
                            <div class="card-section-main border-0 card-lifestyle">
                                <img src="../../public/ideas-anime.webp" alt="" class="card-img">
                                <div class="card-img-overlay">
                                    
                                    <span class="badge text-bg-light -3 py-1 fw-semibold">Culture</span>
                                    
                                </div>
                            </div>

                            <div class="mx-2">
                                <span><i class="fa-solid fa-user"></i></span>
                                <span class="mx-2 fw-bold">demo</span>

                                <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                <span>December 26, 2022</span>
                                <p class="card-text fw-bold">Live Ideas You Might Be Anime</p>
                            </div>
                        </div>
                        <hr>

                        <div class="flex-lifestyle">
                            <div class="card-section-main border-0 card-lifestyle">
                                <img src="../../public/anime-fashion.webp" alt="" class="card-img">
                                <div class="card-img-overlay">
                                    
                                    <span class="badge text-bg-light -3 py-1 fw-semibold">Fashion</span>
                                    
                                </div>
                            </div>

                            <div class="mx-2">
                                <span><i class="fa-solid fa-user"></i></span>
                                <span class="mx-2 fw-bold">demo</span>

                                <span><i class="fa-solid fa-calendar-days mx-2"></i></span>
                                <span>December 25, 2022</span>
                                <p class="card-text fw-bold">Live Ideas You Might Be Anime</p>
                            </div>
                        </div>
                        <hr>
                    </div>
                </div>
            </section>                  <!-- FINE SEZIONE 3 COMPLETA -->
        </div>

        <section class="bg-section mt-5 p-4">   <!-- SEZIONE 4 COMPLETA -->
            <div class="container">
                <div class="">
                    <img src="../../public/page-banner-1.webp" alt="" class="rounded-2 w-100">
                </div>
            </div>
        </section>                              <!--FINE SEZIONE 4 COMPLETA -->

        
        <section class="bg-section mb-4">
            <div class="slider" @mouseover="handleMouseOver" @mouseleave="handleMouseLeave">
                <div class="card" v-for="(slide,i) in slideDue">
                    <div class="card-img-box position-relative">
                        <img :src="slide.image" class="card-img-top w-50 bg-black p-1 h-100 w-100 object-fit-center" alt="...">
                    </div>
                    <div class="card-body text-center position-absolute top-0 start-50 translate-middle-x">
                        <p class="fw-bold text-light badge bg-secondary fs-6">{{ slide.desc }}</p>
                    </div>
                    <div class="text-center position-absolute bottom-0 end-0 translate-middle-x">
                        <p class="fw-bold bg-danger text-light badge fs-7">{{ slide.price }}</p>
                    </div>
                </div>
                        <!-- <p class="fw-semibold">{{ slide.date }}</p> -->
            </div>

            <button class="my-button next" @click="prev"><i class="fa-solid fa-angle-left"></i></button>
            <button class="my-button prev" @click="next"><i class="fa-solid fa-angle-right"></i></button>
        </section>


        <section class="mt-5 mb-5">
                <div class="container">
                    <div class="flex-yt">
                        <div class="player">
                            <iframe width="840" height="550" src="https://www.youtube.com/embed/MmAJq7BBN0A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                        </div>


                        <div class="playlist-yt">
                            <div class="head-playlist">
                                <div class="icon-play">
                                    <i class="fa-solid fa-play"></i>
                                </div>

                                <div class="text-header-playlist">
                                    <p>Video Playlist</p>
                                    <p>1/7 Videos</p>
                                </div>
                            </div>

                             <div class="body-playlist">
                                <ul>
                                    <li v-for="(video, i) in videos" :key="i">
                                        <div class="flex-video">
                                            <div class="number-video">
                                                {{ video.num }}
                                            </div>

                                            <div class="thumb-video">
                                                <img :src="video.thumb" alt="">
                                            </div>

                                            <div class="title-video">
                                                {{ video.title }}
                                            </div>
                                        </div>
                                    </li>
                                </ul>
                            </div> 
                        </div>
                    </div>
                </div>
            </section>



            <section class="my-5">                    <!-- INIZIO SEZIONE 7 COMPLETA -->
            <div class="flex-footer-top">
                <div v-for="(card,i) in carouselFoot">
                    <div class="card-pers">
                        <div class="flex-title-footer">
                            <div>
                                <h5 class="text-center">{{card.title}}</h5>
                            </div>

                            <div>
                                <h5 class="text-center">{{ card.desc }}</h5>
                            </div>
                        </div>
                        <img :src="card.image" class="img-card-pers" alt="">
                        <div class="white-square">
                        </div>
                        <div class="overlay-pers"></div>
                        
                    </div>
                </div>
            </div>        
        </section>                             <!-- FINE SEZIONE 7 COMPLETA -->

        

    </main>

    <AppFooter />

</template>

<style lang="scss" scoped>
.bg-section{
    background-color:#F3F3F3;
    padding: 30px;
    position: relative;
}
        
.slider{
    display: flex;
}

.card{
    margin: 0 10px;
    max-height: 300px;
}

.card-img-box {
    height: 300px;
    
    .card-img-top {
        max-height: 300px;
        width: 100%;
        object-fit: cover;
        object-position: top;
        border-radius: 5px;
    }
}




.my-button{
    color: #DF693C;
    border: none;
    background-color: white;
    padding: 10px 16px;
    border-radius: 100px;

    i{
        font-size: 18px;
    }
}


.next{
    position: absolute;
    top:180px;
    left: 60px;
}

.prev{
    position: absolute;
    top: 180px;
    right: 60px;
}

.my-button:hover{
    background-color: #DF693C;
    color: white;
    transition: 0.2s ease-in-out;
}


.card-body p:nth-child(2){
    color: gray;
}



.my-badge-pers1{
    position: absolute;
    top: 0;
    left: 25%;
    margin:10px;
    padding: 5px 15px;
    margin-left: 30px;
}

.my-badge-pers2{
    position: absolute;
    top: 0;
    left: 50%;
    margin-top: 10px;
    padding: 5px 10px;
    margin-right: 70px;
}

.container{
    max-width: 1200px;
}

.card-positive{
    position: relative;
}

.text-overlay{
    position: absolute;
    top: 120px;
    left: 12px;
}

.text-overlay-center{
    position: absolute;
    top: 320px;
    left: 170px;
}

.card-section-main img{
    filter: brightness(0.5);
}

.card-section-main{
    cursor: pointer;
    transition: 0.5s;
    filter: contrast();
}
.card-section-main:hover{
    cursor: pointer;
    filter: contrast(0.6);
    transition: 0.5s;
}

.text-center span{
    margin-top: 10px;
}
/* FINE CSS SEZIONE 2 */

.flex-section{
    display: flex;
    justify-content: space-between;
    align-items: center;

    h4{
        font-weight: bold;
    }
}

.card-img-overlay span{
    margin-top: 10px;
}


.badge-pers{
    background:#555454;
    padding: 8px 16px;
    margin-right: 15px;
    font-weight: 500;
}

.badge-pers:hover{
    background-color: #bf1d2e;
    cursor: pointer;
}

.card-lifestyle-text{
    position: absolute;
    top: 370px;
}

.flex-lifestyle{
    display: flex;
    align-items: center;
}

.card-lifestyle{
    width: 35%;
}

hr{
    color: black;
}

.flex-lifestyle .card-img-overlay{
    padding: 2px 10px;
}

/* FINE CSS SEZIONE 3 */

.bg-section{
    background-color:#F3F3F3;
}

/* FINE CSS SEZIONE 4 */




/* fine sezione 5 */

.card-carousel-width{
    width: 200px;
}


/* fine sezione 6 */


.flex-video{
    display: flex;
    align-items: center;
    padding: 10px;


> .thumb-video{
        width: 100px;
        margin: 15px;
        cursor: pointer;
    }
    .thumb-video img{
        object-fit: cover;
        width: 110px;
        height:80px;
        
    }
}

.body-playlist li:not(:last-child){
    border-bottom: 1px solid black;
}

ul,ol{
    list-style: none;
    padding: 0;
}


.number-video{
    background-color: #252525;
    color: white;
    padding: 1px 7px;
    border-radius: 5px;
    font-size: 14px;
}

.number-video:hover{
    background-color:#bf1d2e ;
    cursor: pointer;
    transition: 0.2s ease;
}
     
.title-video{
    font-size: 13px;
    margin-left:10px;
    font-weight: 500;
}

.title-video:hover{
    color: #bf1d2e;
    transition: 0.2s ease;
    cursor: pointer;
}


    /* sezione yt */

.flex-yt{
    display: flex;
    height: 550px;

> div:nth-child(1){
        width: 70%;
    }

> div:nth-child(2){
        width: 30%;
    }
}

.head-playlist{
    display: flex;
    height: 90px;
    background-color: #252525;
    padding:10px;
    align-items: center;
    padding-left: 20px;

> div i, div p{
        color: white;
    }

    div p{
        margin: 0;
        margin-left: 15px;
        font-size: 14px;
    }

    div i{
        font-size: 35px;
    }
}



.body-playlist{
    height: calc(100% - 90px);
    background-color: #F3F3F3;
    overflow-y: auto;
}

.slider2{
    display: flex;

    .card{
        border: none;
    }
}


.link-pers{
    text-decoration: none;
    color: white;
    background-color: #bf1d2e;
    padding: 10px 35px;
    border-radius: 20px;
    font-weight: 600;
}

.link-pers:hover{
    background-color: #333333;
    transition: 0.3s ease;
}

.slider2 .card-body{
    background-color: #F3F3F3;
}

.slider2 .card-body p:nth-child(2){
    color: gray;
}

.flex-section{
    display: flex;
    justify-content: space-between;
    align-items: center;

    h4{
        font-weight: bold;
    }
}

.my-button2{
    border: none;
    background-color:#333333;
    color: white;
    padding: 10px 16px;
    border-radius: 100px;
    margin: 0 10px;
}

.my-button2:hover{
    background-color: #bf1d2e;
    transition: 0.2s ease;
}


.flex-footer-top{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap; 
    overflow-x: hidden;
            
    > *{
        width: calc(100% / 6 - 20px) ;
        margin: 0px 10px;
        }
}   
    

.card-pers{
    width: 100%;
    height: 200px;
    margin:0 5px;
    overflow: hidden;
    border-radius: 5px;
    position: relative;

    .flex-title-footer div:nth-child(1) h5{
        position: absolute;
        z-index: 1;
        color: white;
        font-weight: bold;
        font-size: 22px;
        top: 30%;
        left: 33%;

    }


    .flex-title-footer div:nth-child(2) h5{
        position: absolute;
        z-index: 1;
        color: white;
        font-weight: bold;
        font-size: 18px;
        top: 60%;
        left: 25%;
        opacity: 0;
        z-index: 1;
        transition: 0.3s;

    }

        .img-card-pers{
        width:100%;
        height: 100%;
        transform: scale(1.4) translateX(-20px);
        transition: transform 0.3s ease;
        filter: contrast(0.5) brightness(0.9);      
    }

    
}

    
.card-pers:hover .flex-title-footer div:nth-child(2) h5{
    transform: translateX(50%);
    opacity: 1;
}

.overlay-pers{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color:rgba(255, 0, 0, 0.3);
    opacity: 0;
    transition: opacity 0.3s ease;
}

.white-square{
    width: 80%;
    height: 70%;
    border: 1px solid white;
    top: 30px;
    left: 33px;
    position: absolute;
    transform:translateX(-40px);
    opacity: 0;
    z-index: 1;
    transition: 0.3s;
    

    h5{
        color: white;
        font-weight: bold;
        position: absolute;
        top: 90px;
        left: 90px;
        font-size: 16px;
    }
}
.card-pers:hover .img-card-pers,
.card-pers:hover .overlay-pers{
    transform: scale(1.4) translateX(20px);
    opacity: 1;
    cursor: pointer;
}

.card-pers:hover .white-square{
    transform: translateX(48px);
    transition: transform 0.3s ease;
    opacity: 2;
    left: -18px;
}


</style>
