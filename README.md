# last-child-of-ligne
last-child-of-ligne

Ce code Permet d'ajouter une class dans la dernière liste dans la ligne


document.querySelectorAll('#alm-filter-nav .filters-item').forEach(function(item) {
    var offsetLeftActList = item.offsetLeft + item.offsetWidth;
    var parent = item.parentElement;
    var offsetLeftAct = parent.offsetLeft + parent.offsetWidth;

    if (offsetLeftActList === offsetLeftAct) {
        item.classList.add('yeeeees');
    }
});
