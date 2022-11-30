<template>
     <div class="content2" id="idcontent" >
            <div class="isicontent">
                <div class="textshiping"><p><center><strong>Shiping Form</strong></center></p></div>
                <form>
                    <div class="isi">

                        <div class="first">
                            <p>First Name</p>
                            <div>
                                <input type="text" placeholder="Your First Name" required id="firstname">
                            </div><p></p>
                            <p>Last Name</p>
                            <div>
                                <input type="text" placeholder="Your Last Name Number" required id="lastname" >
                            </div><p></p>
                            <p>Email Adress</p>
                            <div>
                                <input type="email" placeholder="Your Email Adress" >
                            </div>
                        </div>

                        <div class="second">
                            <p>Phone Number</p>
                            <div>
                                <input type="number" placeholder="Your Phone Number" >
                            </div><p></p>
                            <p>City</p>
                            <div>
                                <input type="text" placeholder="Input City" >
                            </div><p></p>
                            <p>Postal Code</p>
                            <div>
                                <input type="number" placeholder="Input PostaL Code" >
                            </div>
                        </div>
                    </div><p></p>

                    <div class="adress">
                    <p>Address</p>
                        <p><textarea type="text" name="" id="alamatrumah" cols="53" rows="3" placeholder="Input Your Address"  required></textarea></p>
                    </div>
                    <div class="buttonsubmit">
                        <button type="" class="btn-success" id="btnsubmit2">submit</button>
                    </div>
                </form>
            </div>
    </div>
</template>

<script>
export default {
    name: 'ShipingComponents'

}
</script>

<style scoped>
.content2{
    height: 590px;
    display: flex  ;
    justify-content: space-around;
    border: 2px solid grey;
    border-radius: 2%;
    width: 570px;
    margin-left: 30%; 
    background-color: bisque;
}
.isi{
    display: flex;
    justify-content: space-around;
}
.textshiping{
    margin-top: 4%;
    font-family: sans-serif;
    font-size: 26px;
    font-style: bold;
}


</style>