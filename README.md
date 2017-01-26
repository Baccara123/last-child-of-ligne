# last-child-of-ligne
last-child-of-ligne

Ce code Permet d'ajouter une class dans la dernière liste dans la ligne


 $('#alm-filter-nav .filters-item').each(function() {
        var offsetLeftActList = $(this).offset().left + $(this).outerWidth();
        var offsetLeftAct = $(this).parent().offset().left + $(this).parent().outerWidth();
        if(offsetLeftActList == offsetLeftAct){
            $(this).addClass('yeeeees');
        }
    });
