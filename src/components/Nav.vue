<template>
    <div class="nav-container container">
        <div class="nav-logo">
            <img src="../assets/dc-logo.png" alt="">
        </div>

        <div class="nav-menu">
            <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Shop</a></li>
            </ul>
        </div>
    
    </div>
    
</template>

<script>
export default {
    name:"Nav"    
}
</script>


<style lang="scss" scoped>
    .nav-container {
        display: flex;
        justify-content: space-between;
        align-items: center;

        .nav-logo {
            img {
                width: 80px;
            }

        }

        .nav-menu {
            ul {
                display: flex;
                li {
                    margin: 0 18px;
                    text-transform: uppercase;
                    border-bottom: 4px solid white;
                    height: 120px;
                    line-height: 120px;
                    font-weight: 500;

                    &:hover {
                        border-bottom: 4px solid #18f;
                        cursor: pointer;
                        color: #08f;
                    }
                }
            } 

        }
    }


</style>