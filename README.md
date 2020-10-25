# fengsheng
a little repository
public class User{

    public static void main(String[] args){
        Thread thread = new Thread(new Runnable{
            run(){
                System.out.println("创建线程");
            }
        });
    }
}
