package vsltest2;

import java.io.File;
import java.io.IOException;
import java.nio.charset.Charset;
import java.util.LinkedHashMap;
import pl.edu.zut.wi.vsl.app.VslException;
import pl.edu.zut.wi.vsl.commons.Message;
import pl.edu.zut.wi.vsl.commons.StegoImage;
import pl.edu.zut.wi.vsl.commons.StegoPackage;
import pl.edu.zut.wi.vsl.commons.steganography.DecodingException;
import pl.edu.zut.wi.vsl.commons.steganography.EncodingException;
import pl.edu.zut.wi.vsl.modules.steganography.lsb.LsbImpl;

//import pl.edu.zut.wi.vsl.app.modules.EncoderModule;
//import pl.edu.zut.wi.vsl.app.modules.InputModule;
import java.util.ArrayList;

public class VSLTest2 {

    public static void main(String[] args) throws VslException {

        for (String c : Charset.availableCharsets().keySet()) {
            //System.out.println(c);
        }

        File f = new File("C:\\Users\\Aaron\\desktop\\fractal.jpg");
//        File f = new File("C:\\Users\\Aaron\\desktop\\grayscale.png");
//        File f = new File("C:\\Users\\Aaron\\desktop\\angryFace.png");
//        File f = new File("C:\\Users\\Aaron\\desktop\\sixteen.png");
        if(!f.exists())
        {
            System.out.println("ajpNote: failed to load image");
        }

//        String s = "ab";
//        String s = "Hello World!";
        String s = "Hello Worlddddo";
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd"
//                + "dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd!";
        
        byte[] bytes = s.getBytes(Charset.forName("ISO-8859-1"));
 
//        System.out.println("bytes     = " + bytes);
//        System.out.println("bytes2Str = " + bytes.toString());
//        System.out.println("bytesStr  = " + new String(bytes, Charset.forName("ISO-8859-1")));

//        System.out.println("Input Message       = " + new String(s.getBytes()));
//        System.out.println("Input Message Bytes = " + s.getBytes());

        Message m = new Message(bytes);

        System.out.println("Input Message       = " + new String(m.getBytes()));
        System.out.println("Input size          = " + m.getSize());
        System.out.println("Input bytes         = " + m.getBytes());
        System.out.println("Input path          = " + m.getPath());
        System.out.println("InputToString       = " + m.toString());
        System.out.println("");

        try {
            StegoImage si = new StegoImage(f);
            StegoPackage sp = new StegoPackage(si, m);
            si.flush();

            LinkedHashMap<String, String> map = new LinkedHashMap<String, String>();
            map.put("startbits", "0");
            map.put("endbits", "3");

            LsbImpl lsb = new LsbImpl();

            try {

                StegoImage sf = lsb.encode(sp, map);
//                sf.write("C:\\users\\aaron\\desktop\\testGrayScaleEncoded.png");
//                sf.write("C:\\users\\aaron\\desktop\\sixteen_enc.png");
                sf.write("C:\\users\\aaron\\desktop\\testEncoded.jpg");
//                sf.write("C:\\users\\aaron\\desktop\\angryFaceEncoded.png");
//                File f2 = new File("C:\\users\\aaron\\desktop\\testGrayScaleEncoded.png");
//                File f2 = new File("C:\\users\\aaron\\desktop\\sixteen_enc.png");
//                File f2 = new File("C:\\users\\aaron\\desktop\\testEncoded.jpg");
//                File f2 = new File("C:\\users\\aaron\\desktop\\angryFaceEncoded.png");
//                StegoImage si2= new StegoImage(f2);

                try {
                    Message mb = lsb.decode(sf, map);
//                    String foo = new String(mb.getBytes(), Charset.forName("ISO-8859-1"));
//
//                    System.out.println("foo=" + foo);
                    
                    System.out.println("Decoded message        = " + new String(mb.getBytes()));
                    System.out.println("Decoded size           = " + mb.getSize());
                    System.out.println("Decoded bytes          = " + mb.getBytes());
                    System.out.println("Decoded Path           = " + mb.getPath());
                    System.out.println("DecodedToString        = " + mb.toString());

                } catch (DecodingException ex) {
                    System.out.println("Error decoding Message: " + ex.getMessage());
                }

            } catch (EncodingException ex) {
                System.out.println("Error encoding: " + ex.getMessage());
            }

        } catch (IOException ex) {
            System.out.println("Error creating StegoImage and Package: " + ex.getMessage());
        }

    }
}
//
//Sample output:
//run:
//Input Message Bytes=[B@a90653
//Input Message=test
//Input Message m=test
//Decoded bytes =[B@1be2d65
//Decoded message =    
//BUILD SUCCESSFUL (total time: 2 seconds)
