# internship
function truncateString(str, num) {
  // Clear out that junk in your trunk
  if (str.length > num && num > 3) {
    return str.slice(0, (num - 3)) + '...';
  } else if (str.length > num && num <= 3) {
    return str.slice(0, num) + '...';
  } else {
    return str;
  }

}

truncateString("<p class="paragraph">Turnip greens yarrow ricebean rutabaga endive cauliflower sea  lettuce kohlrabi amaranth water <a href="https://www.google.pl/search?q=spinach" class="link">spinach</a> avocado daikon Süßkartoffel napa cabbage <strong>asparagus winter purslane kale. Celery potato scallion desert</strong> raisin horseradish spinach carrot soko. Lotus root water spinach fennel kombu maize <span style="font-size: 19px;color: blue;">bamboo shoot green bean swiss chard seakale pumpkin onion chickpea gram corn pea.</span> Brussels sprout coriander water chestnut gourd swiss chard wakame kohlrabi beetroot carrot watercress. Corn amaranth salsify bunya nuts nori azuki bean chickweed potato bell pepper artichoke.</p>", n);
