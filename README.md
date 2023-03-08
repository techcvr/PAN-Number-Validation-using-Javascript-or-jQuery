# PAN Number Validation using Javascript or jQuery

```jquery
<script type="text/javascript">    
$(document).ready(function(){     
        
$(".pan").change(function () {      
var inputvalues = $(this).val();      
  var regex = /[A-Z]{5}[0-9]{4}[A-Z]{1}$/;    
  if(!regex.test(inputvalues)){      
  $(".pan").val("");    
  alert("invalid PAN no");    
  return regex.test(inputvalues);    
  }    
});      
    
});    
</script>    
```
```html
PAN : <input type="text" class="pan">    
```
