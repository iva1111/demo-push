  public Conditioner(int id, String name, int maxTemperature, int minTemperature,
                       int currentTemperature, boolean on) {
        this.id = id;
        this.name = name;
        this.maxTemperature = maxTemperature;
        this.minTemperature = minTemperature;
        this.currentTemperature = currentTemperature;
        this.on = on;
    }

    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }
