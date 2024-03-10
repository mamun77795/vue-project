<script setup>
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>
<template>
    <div class='container'>
        <div class='item1'>
            Step 5
        </div>
        <div class='item2'>
            Customize your wristbands
        </div>
    </div>
    <div class='container'>
        <div class='item3'>
            <h3>Message Style : </h3>
            <input type='checkbox' class='input1' name='check'> <span class='sp1'>Continue Message</span>
            <input type='checkbox' class='input1' name='check'> <span class='sp1'>Font/Back</span>
            <input type='checkbox' class='input1' name='check'> <span class='sp1'>No Message</span>
        </div>
    </div>
    <div class='container'>
        <div class='item4'>
            <div class='border'>
            
            </div>
        </div>
    </div>
    <div class='container'>
        <div class='item5'>
            <h3>
                <i>Indside Message (Optional)</i>
            </h3>
        </div>
    </div>
    <div class='container'>
        <div class='item6'>
            <div>
                <h4>Font Message</h4>
                <input type='text' class='input2' placeholder='Font Message'>
            </div>
            <div class='container2'>
                <div class='item7'>
                    <h4>Choose Font</h4>
                    <input class='btn' type='button' value='Roboto'>
                </div>   
                <div class='item8'>
                    <h4 class='margin'>Choose Color</h4>
                    <select class='select'>
                        <option></option>
                    </select>
                </div>               
            </div>
            <div class='container2'>
                <div class='item7'>
                    <h4>Front Clipart</h4>
                    <select class='btn'>
                        <option class='option'>Choose Start Clipart</option>
                    </select>
                </div>   
                <div class='item8'>
                    <h4 class='dot'>.</h4>
                    <select class='select'>
                        <option class='option'>Choose End Clipart</option>
                    </select>
                </div>               
            </div>
            <div class='container2'>
                <div class='item7'>
                    <input type='button' value='Upload your own artwork' class='btn btn2'>
                </div>   
                <div class='item8'>
                    <input type='button' value='Upload your own artwork' class='select btn2'>
                </div>            
            </div>
        </div>
        <div class='item6'>
            <div>
                <h4>Back Message</h4>
                <input type='text' class='input2' placeholder='Back Message'>
            </div>
            <div class='container2'>
                <div class='item7'>
                    <h4>Choose Font</h4>
                    <input class='btn' type='button' value='Roboto'>
                </div>   
                <div class='item8'>
                    <h4 class='margin'>Choose Color</h4>
                    <select class='select'>
                        <option></option>
                    </select>
                </div>               
            </div>
            <div class='container2'>
                <div class='item7'>
                    <h4>Back Clipart</h4>
                    <select class='btn'>
                        <option class='option'>Choose Start Clipart</option>
                    </select>
                </div>   
                <div class='item8'>
                    <h4 class='dot'>.</h4>
                    <select class='select'>
                        <option class='option'>Choose End Clipart</option>
                    </select>
                </div>               
            </div>
            <div class='container2'>
                <div class='item7'>
                    <input type='button' value='Upload your own artwork' class='btn btn2'>
                </div>   
                <div class='item8'>
                    <input type='button' value='Upload your own artwork' class='select btn2'>
                </div>            
            </div>
        </div>
    </div>
    
</template>


<style scoped>
    .container{
        margin: 0 auto;
        display:flex;
        width: 100%;
        background: dark;
    }

    .container2{
        margin-top: 10px;
        display:flex;
        width: 100%;
        background: dark;
    }
    .item1{
        background: #662d91;
        color: white;
        font-weight: bold;
        padding: 7px;
        padding-left: 15px;
        width: 10%;
        font-size:1.3rem;
    }

    .item2{
        background: gray;
        color: white;
        padding: 7px;
        width: 100%;
        font-size: 1.1rem;
        font-weight: bold;
    }

    .item3{
        display: flex;
        margin-top: 15px;
        margin-left: 110px;
        margin-right: 110px;
    }
    h3{
        font-weight: bold;
    }
    .input1{
        height: 20px;
        width: 20px;
        margin-top: 15px;
        margin-left: 15px;
        margin-right: 15px;
        color: blue;
    }
    .sp1{
        margin-top: 13px;
    }
    .item4{
        border: 0.5px solid gray;
        width: 80%;
        height:80px;
        display: flex;
        margin-top: 15px;
        margin-left: 110px;
        margin-right: 110px;
    }
    .border{
        width:100%;
        height: 85%;
        margin: 5px;
        border: 2px dashed gray;
        border-spacing: 15px;
    }
    .item5{
        border: 0.5px solid gray;
        width: 80%;
        height:80px;
        margin-top: 15px;
        margin-left: 110px;
        margin-right: 110px;
        font-size: 1.2rem;
    }
    h3{
        text-align: center;
        margin-top:17px;
        color: gray;
    }
    .item6{
        width: 100%;
        padding: 30px;
    }

    .item7, .item8{
        width: 100%;
        margin-top: 10px;
        font-size: 1.2rem
    }
    .input2{
        width:100%;
        font-size:1.2rem;
        border-radius: none;
        padding: 5px;
        margin-top: 10px;
    }
    .item7{
        
        width:100%;
    }
    .btn{
        margin-right: 20px;
        width: 90%;
        height: 38px;
        border-radius: 15px;
        font-size: 1.2rem
    }
    .select{
        margin-left: 20px;
        width: 90%;
        height: 38px;
        border-radius: 15px;
        padding-right: 10px;
        font-size: 1.2rem
    }
    .btn2{
        border: none;
        background: #242448;
        color: white;
        font-size: 1rem;
    }
    h4{
        font-size: 1.2rem;
        margin-bottom: 5px;
    }
    .option{
        background: green;
        font-size: 0.7rem;
       margin-left: 6px;
    }
    .margin{
        margin-left: 16px;
    }
    .dot{
        color: white;
    }
</style>