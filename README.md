package coordinates;

public class ChildLocation extends Locations{
    public ChildLocation(double x, double y, double z) {
        super(x, y);
        this.z = z;
    }

    public ChildLocation(double x, double y) {
        super(x, y);
        z = 0;
    }

    public ChildLocation() {
        super(0, 0);
        this.z=0;
    }

    @Override
    public String toString() {
        return super.toString() + "z=" + z + '}';
    }

    private double z;


}
