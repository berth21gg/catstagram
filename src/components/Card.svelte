<script>
    import mostacho from '../assets/cat01.jpg';
    import Comments from './Comments.svelte';
</script>

<div class="Card">
    <div class="Card-container">
        <div class="Card-header">
            <div class="Card-user">
                <img src={mostacho} alt="">
                <h2>
                    mostacho.cat
                    <span>Guanajuato, México</span>
                </h2>
            </div>
            <div class="Card-settings">
                <i class="fa-solid fa-ellipsis"></i>
            </div>
            <div class="Card-photo">
                <figure>
                    <img src={mostacho}  alt="">
                </figure>
            </div>
            <div class="Card-icons">
                <div class="Card-icons-first">
                    <i class="fa-solid fa-heart"></i>
                    <i class="fa-solid fa-paper-plane"></i>
                </div>
                <div class="Card-icons-seconds">
                    <i class="fa-solid fa-bookmark"></i>
                </div>
            </div>
            <div class="Card-description">
                <h3>mostacho.cat</h3>
                <span>Hola</span>
            </div>
            <Comments />
        </div>
    </div>
</div>