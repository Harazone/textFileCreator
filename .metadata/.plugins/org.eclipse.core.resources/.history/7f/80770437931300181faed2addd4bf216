package textPackage;

import java.io.BufferedWriter;
import java.io.FileNotFoundException;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;
import java.io.UnsupportedEncodingException;

public class TextMain {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		PrintWriter writer;
		
		try(FileWriter fw = new FileWriter("C:/Users/hara/Desktop/TextFile/test.txt", true);
			    BufferedWriter bw = new BufferedWriter(fw);
			    PrintWriter out = new PrintWriter(bw))
			{
			    out.println("the text");
			    //more code
			    out.println("more text");
			    //more code
			} catch (IOException e) {
			    //exception handling left as an exercise for the reader
			}	
		
		
	}

}
