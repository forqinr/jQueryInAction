#Radio

1.get a checked radio

  `$("[property='protertyName']:checked")`
  
  eg.
  
    `$("[name='IS_PURCHASE_CONTRACT']:checked")`
    
    get the checked radio value
    
    `$("[name='IS_PURCHASE_CONTRACT']:checked").val()`

2.radio disable

  `$("[name='EXPENDITRUE_TYPE']").attr("disabled","disabled")`
  
3.All radios in the page add a class

  `$(":radio").addClass("radioStyle")`
