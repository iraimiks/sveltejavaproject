<script>
    let date = new Date();
    let nowHoer = date.getHours();
    let daysStamp = 14;
    let count = 0;
    let houersOfDay = [];
    while(count < daysStamp){
        houersOfDay[0] = count;
    count++;
    console.log(houersOfDay);
    }
    
</script>
<div>
{date}
{nowHoer}
</div>

