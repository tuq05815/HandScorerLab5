# HandScorerLab5
Lab5

public class HandScorer implements HandScorerInterface{


    public int score(StackInterface<Card> hand) {
    	int total = 0;
    	int numAces = 0;
    	int numCards;
    	
    //	Card card = card.remove(card.size()-1);
    	public boolean addCard(Card card) {
    		if (this.numCard == 10) {
    			return data;
    			
    	
    		}
    	}
    	
    	for (int i = 0; i < this.numCards; i++) {
    		numCard = this.value[i].getValue();
    	}
    	
    	return total;
    	
    	
    	while (hand.isEmpty()) {
    		Card card = hand.pop();
    		String value = card.getValue();
    		
    	//computes values for ace for 10 vs 11 (1 v 10)	
    		if (value.equals("ace")) {
    			numAces++;
    			total += 11;
    		}else if (!value.equals("ace")) {
    			total += 10;
    		} else {
    			total += (value);
    		
    		}
    	}
    	
    	while (Acenum > 0 && total >21) {
    		total -= 10;
    		numAces--;
    	}
    	
    	return total;
    	
    	if (dealerScore > playerScore) {
    		return dealer;
    	}
    	}
}
    //event of tie for dealer to win
