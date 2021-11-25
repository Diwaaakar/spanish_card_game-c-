# spanish_card_game-c-
spanish card_game c3

Create Class DeckOfCards as member a list of SpanishPlayingCard. Constructor of 
the class must to create a Deck of Cards with the 48 SpanishPlayingCard


using System; 
using System.Collections.Generic; 
using System.Linq; 
using System.Text; 
using System.Threading.Tasks; 
namespace Ques3 
{ 
 class SpanishPlayingCard 
 { 
 private int number; 
 private string sign; 
 public SpanishPlayingCard() 
 { 
 number = 0; 
 sign = ""; 
 } 
 public SpanishPlayingCard(int numParam, string signParam) 
 { 
 number = numParam; 
 sign = signParam; 
 } 
 public void WriteCardValue() 
 { 
 Console.WriteLine("Card Details \n"); 
 Console.WriteLine("Number: "+ number+ "\n"+ "Sign: "+ sign); 
 } 
 } 
 class DeckOfCards 
 { 
 public List<SpanishPlayingCard> cards = new List<SpanishPlayingCard>(48); 
 public int numOfCards() 
 { 
 return 48; 
 
 Console.ReadKey(); 
 } 
 } 
}
